# Capital BikeShare System Data Exploration

### by Clarence Beling

## Dataset

The data consists of information regarding 158,130 bike records by race, including times, stations, and bike qualities. This dataset of February 2019 can be downloaded in the [Washington DC Metro Area](https://s3.amazonaws.com/capitalbikeshare-data) link. However it needed extraction of other data to continue exploration.

## Summary of Findings

In the exploration of main data, extracted data 1 and extracted data 2, we found that there was a strong relationship between the time, type and races variables. So this relationship is approximately linear between time and races variables when time is transformed to be on a logarithmic scale. We found a interesting result initially when the type variable indicated that Member majority quality was more associated with shorter times and it was less associated with Casual minority quality. When we looked at number of participants, we found that it decreased as the races followed each other.

Otherwise, we verified the relationship between the races and participants variables. For the `capital_race` dataset, there was an interesting interaction in the type quality values. The Casual bike type minority looked impredictable, so few races had Casual biker type majority.

## Key Insights for Presentation

For the presentation, we focused on just the influence of the type and time variables. We start by introducing the type variable, followed by the time variable. Afterwards, we introduce the two other variables one by one.

To start, we used violin, box and bar plots of times and types to look at the performance (best time) of each biker type ; The races, times and types variables are covered using point plots ; And the races, participants and types variables, using line plots. We used different color palettes for each type to make sure it is clear that they are different between plots.
