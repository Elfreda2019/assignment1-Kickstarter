# Kickstarter Analysis
## Project Overview
 Louise is an up and coming play writer who wants to start a crowdfunding campaign to help fund her play, Fever. She is estimating a budget of over $10,000 and hesistant about starting the fundraising campaign. We are going to run analysis on Kickstarter data using Excel to provide Louise with helpful insight based on campaigns that has already been held in order to have a successful campaign.

## Analysis and Challenges
#### Description
First we try to understand the Kickstarter data including all variables present. Then we sorted, filtered and formatted our data. We made our data more detailed by splitting the Category and subcategory into 2 separate columns in order to get more information on the data. Since we know Louise is interested in play, we can tell from our data that play is a subcatergory under the parent catergory theater. We generated new columns which are variables such as Years(from the Date Created Conversion column) among others. 

#### Visuals and Tables
We went ahead and created a pivot table on a new sheet from the Kickstarter worksheet with filters based on Parent Category and Years named [Theater Outcomes by Lunch dates](https://github.com/Elfreda2019/assignment1-Kickstarter/blob/main/Kickstarter_Challenge.xlsx.zip) . Theater was filtered and a line chart was plotted showing the visual relationship between outcomes and launch date. As shown in figiure 1.

#####

![Image as shown](https://github.com/Elfreda2019/assignment1-Kickstarter/blob/main/Resources/Theather_Outcomes_vs_Launch.png)
figure 1
#####
In order to get a clearer picture of the outcomes which are successful, failed and canceled based on the goal, on a new sheet we created grouped ranges for the goal in dollars and filtered play from the subcategory along side. Then we populated the number count of each outcome based on the filtered data on a new sheet named Outcomes based on Goals and also computed their individual percentages and totals as shown in the [excel zip file](https://github.com/Elfreda2019/assignment1-Kickstarter/blob/main/Kickstarter_Challenge.xlsx.zip). And finally plotted a line chart to visualize the relationship between the goal amount ranges on the x-axis and percentages of sucessful, failed and canceled on the y axis. As shown in figure 2. 
##### 

![image as shown](https://github.com/Elfreda2019/assignment1-Kickstarter/blob/main/Resources/Outcomes_vs_Goals.png) 
figure 2

### Challenges

During the formatting, filtering and sorting stage  we encounted a few challenges, because some of the campaigns had no backers, which gave us an error in the calculation of our avearage donation. We used the IFERROR function to set all error entries to 0, because we needed a numerical value for that column. 


## Results
Looking at figure 1 Theater Outcomes by Lunch dates, we found that theater campaigns held in the month of May were the most successful even though the same month of May recorded the most number of failed campaigns as well.
#####
The month of December is not a favourable month for play campaigns based on the our line chart analysis.

#####
From figure 2 Outcome based on Goals, we see that campaigns with goals higher than $4999 are less successful, so knowing Louise has a goal of over $10000. We can advice Louise to reconsider reducing the goal amount to about $4999 in order to have a chance of being successful.

### Recommendation and Limitation
The data is a from different parts of the world and under the currency column several other currencies were recorded, however only dollars were recorded in the goal and pledge column.

####
We could have dived further to look at the pivot table with filtering based on subcatergory 

We also could have also looked at a table of the difference between the lunch date and deadline date to known if the duration of a campaign will impact the outcome of the campaign.


