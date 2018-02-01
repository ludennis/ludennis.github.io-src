Title: Kalman Filter #1
Author: Dennis Lu
Slug: kalman-filter-1
Date: 2018-02-01
Category: Linear Algebra
Tags: linearalgebra, math, learning
Summary: Learning Kalman Filter #1

# Learning Kalman Filter

This is my first time hearing and learning Kalman Filter. 

When I was getting into Udacity's Linear Algebra Refresh Course in lesson 4, the topic of Kalman Filter was brought up, and no previous lessons in the course have introduced nor explained it. 

So upon Googling it, I have found that MatLab's company MathWorks have some videos about it here:
https://www.mathworks.com/videos/series/understanding-kalman-filters.html


## Basic Understanding

From what I got from the first video, Kalman Filter is basically an algorithm that estimates a value that cannot be directly captured, but by other sources that are indirectly related to it. One of the example the tutorial uses is to show how Kalman Filter is used in estimating the location of a car when only the gyroscope and the odometer were available in the absent of GPS. 

## State Observer

To implement a Kalman Filter, we will use a state observer to check the measeured value with estimated value. The state observer is basically a mathamatical model that takes in the measured input and estimate the output and check against the mesaured output. With it the error of the observation betwee the estimate and mesaured value will be used in a Kalman Filter to find the value that we would like to find.

