# SESSION 10 – TESLA (Edge Detection)

## Aim
To compute edge strength using gradient magnitude in image processing.

## Dataset
Berkeley Edge Dataset
https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/

## Objective
To calculate edge magnitude using horizontal and vertical gradients.

## Formula
|∇| = √(Gx² + Gy²)

## Input
Gx = 5
Gy = 12

## Procedure
Step 1: Read gradient values Gx and Gy
Step 2: Apply edge detection formula
Step 3: Compute edge strength
Step 4: Display result

## Algorithm
Step 1: Start program
Step 2: Input Gx and Gy
Step 3: Compute:
        edge = sqrt(Gx^2 + Gy^2)
Step 4: Store result
Step 5: Display edge strength
Step 6: Stop program

## Code Logic
edge = sqrt(Gx**2 + Gy**2)

## Output
Edge Strength = 13

## Result
Edge magnitude calculated successfully.

## Industry Application
Used in Tesla autonomous driving systems for detecting object boundaries.

## Tools Used
Python
Google Colab
GitHub
