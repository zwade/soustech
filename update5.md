---
layout: base
title: SousTech Milestone Report
---

# SousTech Update 5
#### Zachary Wade &lt;zwade&gt;

## Major Changes

No major changes have occurred.

## Accomplishments

Over the past two weeks I have completed and tested version two of the SousTech hardware. This new version contains two additional sensors, one that can measure the temperature inside the housing (for calibration purposes) and an IR temperature sensor that can measure the approximate temperature of the food that is being prepared. The hope is that these additional data points will allow us achieve more repeatable data by providing a baseline for the data.

## Milestone

While I have not been able to take much new data, I have successfully completed my primary milestone of adding the new sensor and integrating it into the collection pipeline.

## Suprises

There were a few individual surprises; for instance integrating the sensor was difficult because it primarily communicated over I<sup>2</sup>C, and while it had a PWM mode, that required disabling I<sup>2</sup>C permanently and gave 10 bits of resolution instead of 12. This meant that large portions of the protoboard had to be resoldered in order to make room for the new chip. As one might imagine, this lead to a number of random issues (bad solder joints, mislabeled inputs, etc.). None of these were particularly major, however. 

## Looking Ahead

Now that we have the new sensor added, we hope to be able to tell whether or not the data we are collecting is more stable &mdash; i.e. will we be able to get roughly the same data for two instances of the same test.

## Revisions

At this point the main goal is to continue collecting data and determining the feasibility of detection.

## Resources

More food is required for testing purposes.

