# System Programming Lab 11 Multiprocessing
CPE 2600 111

Megan Cranston

## Overview
- The user inputs the settings for the image into the command line, which includes:
  - x and y position
  - x scale (y scale calculated)
  - width and height
  - max iterations
  - num processes
  - num frames
- If no input is entered, default settings will be used
- The program then iterates over the number of frames and creates the appropriate number of processes
- Each process generates a frame and outputs it as a .jpg file

## Runtime Graph
![Runtime Graph](Lab11PlottedData.png)

## Results
- Using only 1 process took almost 3min to complete
- Using 10 processes reduced the time to just over 30s to complete
- Using 20 processes will continue to get slightly faster, but eventually the difference is negligible