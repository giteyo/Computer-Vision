# Geez Number Recognizer

## Overview
This project uses Convolutional Neural Network for Geez number Recognition from 1 to 99.

## Step 1 - Load important libraries
This is important to load.

## Step 2 - Loading Dataset
Visualization of loaded images from Dataset.

## Step 3 - Preprocessing
✅ Resize all images to the same size, e.g., (100,100)
✅ Convert to grayscale
✅ Histogram Equalization
✅ Normalize to 0-1 float

## Step 4 - Prepare Data for Modeling
Steps for batch preprocessing
✅ Convert Images and Labels into Arrays
✅ Encode Labels
✅ Split Dataset into Train and Test Sets

## Step 5 - Build, Train, and Evaluate a CNN with TensorFlow/Keras
✅ Visualize Training Progress

NB: I have tried to collect hand written data from more than 160 students from University of Gondar BSc and MSC students. It is hard to collect, but the dataset preparion was even harder, which rewuires me to crop every character from the captured image, which I collected.

The Dataset preparation had the following stages
✅ The collection process used in one A4 paper 7 students sample was taken 
✅ Every student wrote 10 samples from number 1 to 10 and tenth from 20 upto 100
✅ Cropped 49 characters from 1 A4 in front and Back side.
✅ Finally used Digit combiner script to create 99 characters by combining tenth and once digits. 

Only included 36 samples from totally collected samples as manual croppin is frustrating, if there is any one who could help me make the cropping automated, you are wellcome, Just send message to my Linkedln or email, Thank you!!!
✅ Any one who is interested to access the dataset, please check this link https://drive.google.com/drive/folders/10VUPdH8xQEqd6G8ycMmWE2X68zi7TSfg?usp=sharing.

# Course
Computer Vision
