# Analyzing data on overweight and obesity around the globe

The data is taken from https://ourworldindata.org/obesity
People with a BMI >= 25 are defined as overweight.
People with a BMI >= 30 are defined as obese.
Data is available for the years 1975-2016 for many countries around the globe.


## Reproduce

1) Execute the cells inside the `main.ipynb`
2) To convert the images into a  video execute: `ffmpeg -framerate 1 -i figs/v5_%02d.png -c:v libx264 bmi.mp4`
