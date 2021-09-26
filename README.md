# Kickstarter-Analysis-Challenge-1
##Kickstarter - Analysis 

  The purpose of this analysis was to provide Louise visual documentation on campaign outcomes based on the launch date and the funding goals obtained from kickstarter. Although Louise has already began her fundraiser for her play "Fever", she did not obtain the full funding that she was looking for.  Consequently, Louise is interested in using this information in order to successfuly launch her fundraiser in the future.   
  
  The analysis was performed by taking the data download of Kickstarter campaigns.  At first look the data seemed to be seamless.  However, the dates that were used for deadline and also launch date were in Unix Timestamp.  This posed a problem since most people need to have dates in the gregorian format in order to understand.  This was solved by including the following formula in order to translate the date from the Unix Timestamp to the gregorian calendar, =(((cell i/60)/60)/24) + Date(1970,1,1).  The (1970,1,1) was used as this is beginning of the Unix timestamp.  An additional column for year was added so the data could be looked at by month.  The data was also broken down by subcategory to get a better understanding of just plays within the theater parent category.  

![image](https://user-images.githubusercontent.com/90973718/134826345-6c1ec57b-97d2-4406-bd5c-ea191583fe79.png)

  In conclusion, May and June seem to be the months where the most campaigns were launched and also happens to be the two most successful months for campaigns. Whereas, campaigns launced in December were the lowest and also show a 50/50 chance of being successful or failing.    
  
  Louise was also interested in the results of campaigns based off of their inital goal.  The majority of the campaign goals were less than $15,0000.  This is also were you see the most successful campaigns based off of goal amount.  Once the goal amounts exceeded the $20,000.00 threshold you can see that the percentage of failed exceeded those that were successful.  However, there is an uptick in successful campaigns between the 35,000 and less than 45,000 threshold.  It does need to be noted that the total number of projects in this threshold is significantly less than the below 15,000 goal threshold.  
  
  Although the data seemed to be complete some additional recommendations that Louise can look are to dive deeper into the subcategories.  Right now the data is centered on theatre, Louise could specifically look at plays based on launch date.  In addition she can filter her data by location (country) and also on currency and those success rates.  This can give her a better idea of successful campaigns in her area or if she would want to produce her play in a different area.   
