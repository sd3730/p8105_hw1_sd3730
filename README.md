# p8105_hw1_sd3730

## Overview
This repository contains my work to Homework 1 problems for the P8105 course. It focuses on reinforcing ideas from the "Building Block" topic.
 
## Problem 0.1: Project Setup
- Created a public GitHub repository and a local R Project named `p8105_hw1_sd3730`.
- Developed a single R Markdown file named `p8105_hw1_sd3730.Rmd` that renders to `github_document`.

## Problem 0.2: Code Style
The solutions adhere to the following styling guidelines:
- Meaningful variable and object names.
- Readable code with one command per line, adequate whitespace, and proper indentation.
- Clearly written text to explain code and results.
- No superfluous code (no unused variables or extra library calls).

## Problem 1: Penguins Dataset
- Loaded the penguins dataset from the `palmerpenguins` package.
- Described the dataset using inline R code
- Created a scatterplot of flipper length vs. bill length, colored by species.
- Exported the scatterplot to the project directory using `ggsave`.

## Problem 2: Variable Types and Coercion
- Created a data frame consisting of:
  - A random sample of size 10 from a standard Normal distribution.
  - A logical vector indicating whether elements of the sample are greater than 0.
  - A character vector of length 10.
  - A factor vector of length 10 with three different levels.
- Attempted to calculate the mean of each variable, noting what works and what doesn’t.
- Applied the `as.numeric` function to the logical, character, and factor variables to illustrate type coercion.

## Additional Notes
- All code runs without errors and the .Rmd file can be knitted successfully to confirm reproducibility.

