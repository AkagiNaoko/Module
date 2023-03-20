# Kickstarting with Excel

## Overview of Project
Crowdfunding is a popular method of raising funds for a project, business, or cause. It involves reaching out to a large number of people through an online platform and asking for their financial support. Crowdfunding campaigns have become increasingly popular over the years, with millions of people contributing billions of dollars to various projects around the world.

### Purpose
The purpose of this data analysis report is to examine the performance of crowdfunding campaigns based on their launch date and funding goals. By analyzing this data, we hope to identify patterns and trends that can help us understand what factors contribute to the success or failure of crowdfunding campaigns.

## Analysis and Challenges
One of the challenges of analyzing crowdfunding data is that campaigns can vary greatly in terms of their size, scope, and goals. Additionally, some campaigns may have a longer fundraising period than others, which can make it difficult to compare them directly. Despite these challenges, we can still gain valuable insights by looking at the data as a whole and identifying common patterns and trends.

### Analysis of Outcomes Based on Launch Date
The timing of a crowdfunding campaign can affect its success. 

### Analysis of Outcomes Based on Goals
To analyze the outcomes of crowdfunding campaigns based on their funding goals, we collected data from a popular crowdfunding platform and sorted campaigns into funding ranges. We then calculated the success rate of campaigns for each funding range. The result suggest that size of funding goal are important factors that can influence its success or failure.

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
First, our analysis found that campaigns launched in June, July, and September tended to have the highest success rates, while campaigns launched in August, December and Janurary had the lowest success rates. Additionally, comparing data in different years, campaigns launched in the middle of year tended to have higher success rates than those launched in the other month of the year.


- What can you conclude about the Outcomes based on Goals?
"Goal"
 Goal plays a crucial role in the success of crowdfunding campaigns. Research has shown that campaigns that has goal in the range of 15000~49999 tend to have the high success rates above 70%, with less or more goal campaigns being less successful. Additonally, campaigns with funding goals of less than 14999, has a 50%~70% succeddful rate, while in this range the canceled rate is highest around 30%. Finally, campaigns with funding goals of over 44999 have increased canceled and failed rate during funding goals increasing.

- What are some limitations of this dataset?
"Currency"
The pledged amounts in different countries are in differnt currency. It is impossible to analyze the pledged and average donation without more currency information. (Currency is different at different years.)
"Size"
Campaings in some category like theater, and some sub-category like plays have more data than others. The different between data size makes it difficult to compare them.


- What are some other possible tables and/or graphs that we could create?
"Name"
We can create a table to count how many campaigns were successful, failed, or canceled, or are currently live under per different *name*.
"bankers_count and timing"
We can create a table with a column of `bankers_count`, rows of `Date Created Conversion`, values based on the sum of `bankers_count`, and filters based on `parent category` and `Years`. It will help analyze the bankers preference of timing.
