
# Kickstarting with Excel

## Overview of Project
Louise's play Fever was close to making its fundraising goal in only a short amount of time. Lousie is seeing how other campaigns fare in realation to her when it comes to their own fundraising goals. The main focus is on the category theater and the subcategory plays for this project. 

### Purpose

The purpose of the project is to explore how other plays fared when it comes to their fundraising goals compared to how the play Fever fared. It’s important to see what months plays have the most success because these are the months to focus on when trying to fundraise and launch a play. Also, the purpose is to find what campaign goal amount has the most success and what campaign gial amounts have the least amount of success. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

First I found the Date Created Conversion 
'''=(((J2/60)/60)/24)+DATE(1970,1,1)'''
 and then created a column called year and used Year(Q2) which was the first cell in data created conversion to comb out the year. Then created a pivot table and a line plot that was filtered by the theater category and displayed the months with the number of successful, failed, and canceled plays. However, I wanted to see if the months that theater had the most successful fundraising campaigns was similar for other categories.
 
The results showed that May is the best month for not only theater but for music and all categories. 


### Analysis of Outcomes Based on Goals

First to find the number of successul, failed, and canceled plays I used COUNTIFS. One example of this is when finding how many successful plays had a goal less than 1000 I used this code:
''' =COUNTIFS(Kickstarter_Challenge!D:D,"<1000",Kickstarter_Challenge!F:F, "successful", Kickstarter_Challenge!O:O,"plays")'''
 and there were 141 successful campaigns in this category. Moreoever, the data showed thatcampigns that had a goal between $1,000 to $4,999 had the highest amount of successes. 

### Challenges and Difficulties Encountered

One challenge that could be encountered is deciding how to display the data, in this case the line plot does a good job at tracking the changes when it comes to which months have the highest and lowest fundraising success. 

Another challenge is making these assumptions on how successful a campaign is when the date that it is launched and the date that the campaign ends is not very long and so I think extending the campaign would help with this challenge. 

## Results

### Two Conclusions about the Outcomes based on Launch Date?

1. The top three months for plays with the greatest fundraising sucess are May, June, and July.

2. The least successful fundraising campaign month for plays is December. 

 ### One Conclusion for the Outcomes based on Goals?

1. I can conclude that high fundraising goals don’t always equal a high success rate and the data shows that lowering goals can lead to a better outcome. 

## Limitations

1. One limitation is the data doesn’t show how the same play does in different months with different fundraising goals. 

2. Another limitation is the amount of time its launched to the amoutn of time it ends is not very long, it would be interesting to add another month on to the campaigns and see if it makes a difference. 

## Other Tables

Other possible tables include: 
1. Box and Whiskers Plot
2. Bar Graph
3. Cartesian Graph
4. Histogran
5. Pictogram
6. Pie Charts
