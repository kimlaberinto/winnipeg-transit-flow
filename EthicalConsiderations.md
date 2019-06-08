# Ethical Considerations
> Ethical Considerations for [Winnipeg Transit Flow Visualization](https://github.com/kimlaberinto/winnipeg-transit-flow)

As mentioned in the [README.md](README.md), I believe its important that I take precautions to ensure the visualization does not mislead others.

I wanted to be open regarding ethical considerations that I thought of during this project. 

I know I am not perfect and there will be always a lot more to learn. 

If you have any feedback for me, please let me know. You are also welcome to raise an issue on the GitHub repository.

## Limitation
Unfortunately, I am not sure if I will be able to document all ethical considerations in this file. However I will strive to document the major ones

## Table of Contents
* Overview - Stakeholders
* Clarity between Static vs Realtime Data
  * Solution: 

## Stakeholders
List of stakeholders of this visualization project.

* The public
  * Tax payers funding Winnipeg Transit
  * Transit Riders
  * Other Road Users
  * etc.
* Winnipeg Transit
* City of Winnipeg

## Static vs Realtime Data
### Summary
I decided to label the static schedule data visualization using the word "Simulated" to help distinguish it from realtime data. I do not want to mislead Winnipegers into thinking that the visualization is regarding Winnipeg Transit real time performance.

### Overview of Concern
At the time that I write this, I am intending to explore the static schedule file that Winnipeg Transit provided. This lists the times that buses are meant to arrive at bus stops throughout the day.

At the time that I write this, I do not yet know what the data would look like. However I want to be clear to those who see the visualization that it is only based on the static schedule. They are not meant for any

The reason for this is that I do not want to mislead Winnipegers into thinking that it is real time performance of the buses.

#### Other words considered
* "Static Schedule"
  * Not many would understand what "static schedule" means.
* "Non-realtime"
  * Too clunky. Also might be confusing.
* Simulated based on perfect adherance to the bus schedule"
  * This is a good consideration. For now, might not use it as its too long, however it is accurate.
* "Perfect Bus Schedule Simulation"
  * Might be a good candidate.
* "Perfect Bus Schedule Visualization"
  * Not clear/accurate. Implies that the visulization is 'perfect' and shows a possible improvement.
* "Perfect adherance to bus schedule"
  * Inaccurate in the sense that I don't know the exact speeds that buses would travel down roads. It would have to be inferred and might not be accurate.

### Solution
As of now, I decided to use the word "simulated" to indicate that the bus traffic flow is not real time performance data. I also would like to think that "simulated" shows that there is an inherent subjectivity based on how the simulations or analysis were done. 

I also labeled the data folder in the repository as "static_schedule_data" to hopefully prompt people to think that it is not real-time data.

Other considerations for titles were either too long or not clear enough.

