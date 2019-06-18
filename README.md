# Analyzing data on overweight and obesity around the globe

The data is taken from https://ourworldindata.org/obesity

People with a BMI >= 25 are defined as overweight.

People with a BMI >= 30 are defined as obese.

Data is available for the years 1975-2016 for many countries around the globe.

## Results

An image for each year will be created inside the folder `figs/`. 

These images can be converted into a video via the command below.

As an example, you can see the results for the year 2016 here.

![Results 2016](https://raw.githubusercontent.com/camminady/overweight/master/figs/v5_41.png)



## To reproduce

1) Execute the cells inside the `main.ipynb`
2) To convert the images into a  video execute: `ffmpeg -framerate 1 -i figs/%02d.png -c:v libx264 -profile:v high -crf 20 -pix_fmt yuv420p vid.mp4`

