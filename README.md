# Kickstarting with Excel

## Overview of Project

Based on a extensive database that contains information about various kickstarters around the world with different categories like the outcome, start/end dates, category, subcategory, etc. we will analyze the multiple factors in making a certain type of kickstarter successful. In this occasion it will be primarily focused on theater/plays.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

After filtering by parent category (theater) and outcomes we can conclude that the great majority of plays are successful especially on months like May and June, noting an important drop on months like november and december. So if a recommendation is to be made it would be launching on an interval from April to July, with May being the top choice.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/83614893/147435591-c1860d41-fb37-466c-b8e3-2c8b8a38e8d0.png)
>Image 1. Theater Outcomes vs Launch Graph


### Analysis of Outcomes Based on Goals

For this analysis we visualized the hard numbers of the successful/failed/canceled plays compared to its set goal. The breakdown of the goal numbers were intervals of 5k from 1,000 to 50,000. 

For the **successful** plays the highest rate is found under the 1,000, with 76% of them succeeding around this goal and noting similar increases around the 30k-50k mark with 67% of the plays generating positive results as well.

In the **failed** numbers, we can see that with a notable 100%, all plays with a goal between 45k-50k failed. Just behind with 88% and 80% with the goals set greater than 50k and between 25k-30k respectively. This being important values to consider at the time of setting a goal for your play kickstarter.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/83614893/147437071-a7647f94-74b3-4ce9-85e6-3abc354428d7.png)
>Image 2. Outcomes vs Goals Graph

### Challenges and Difficulties Encountered
For this challenge it was pretty easy to complete after all the practice from the Module if a difficulty is to be listed could be the newly introduced formula of COUNTIFS() due to the syntax that is required to execute the command to its purpose.

## Results

#### What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. The best dates to launch a theater kickstarter are between April and June.
  2. The canceled dates are pretty consistent with a slight peak around October, so it can be a factor to consider.

#### What can you conclude about the Outcomes based on Goals?
If you set a low amount (< $1,000) as your goal the probability of success is greater than a high amount from different donations     being >45k a risk amount to set as your goal.

#### What are some limitations of this dataset?
There are a lot of other factors to take into account in order to make accurate conclusions for a client, also, it would be helpful to get more lines into the dataset and focus on more on each country.

#### What are some other possible tables and/or graphs that we could create?
How many backers a kickstarter has and the outcome.
  
