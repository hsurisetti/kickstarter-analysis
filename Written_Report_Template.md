# **Kickstarting with Excel**

## **Overview of Project**
   The overview of the project is to create two new analyses by analyzing, sorting and representing data, based on goals and launch date to make the project's campaign sucessful. 
      

### **Purpose**

The main pupose of the project is to help Louise to know how different campaigns fared in relation to their launch dates and their funding goals and also show the results visually which can help her even better to assess how each one is performing.


## **Analysis and Challenges**

  
   I analysed the kickstarter challenge spreadsheet by checking how big is the data,  what all the fields represent and what format is assigned to each field.

  Next, I analysed to see what are the tools which could be used to get the results which thereby would help in acheiving better results for example using charts, graphs etc.
     
   Then, created the new columns for Parent category, sub category , Date created conversion and Years. These columns are the essential ones to create the pictorial representation of the outputs in form pivot table and charts. 

### **Analysis of Outcomes Based on Launch Date**

Theater outcomes by launch date mainly depends of the date created conversion column and outcomes.

 Following items involved in analysis
    
  . Created a pivot table with column labels displaying "successful","failed","canceled".

  . Represented row lables with the Months of the date conversion field sorted in ascending order.

  . Created a pivot chart representing months in the x-axis and outcomes in the y-axis.

  . Labelled the title as "Theater outcomes based on launch Date".

### **Analysis of Outcomes Based on Goals**

 Created the spreadsheet for outcomes based on goals with the below details.
 
  . Created each columns based of Number of successful, Number of failed and number of Canceled outcomes and Launch Date months with the criteria of subcategory 'plays' which would show the best months for the campaign.
        
  . Different levels of outcomes ranges like 'less than 1000',between 1000 to 4999 and so on until '50,000 or more' which involved writing excel queries based of COUNTIFS.
        
   . Created a pivot chart and labeled it as 'outcomes based on goal'
        
   . Represented the outcome ranges in x-asis and percentages on the y-axis for percentage successful, percentage failed, Percentage Failed
   
### **Challenges and Difficulties Encountered**

#### **Minor challenges faced** : 
  
  In Deliverables 1, my line chart was showing differently compared to the one it should show as per deliverables. Upon changing the style of the line chart it showed exactly as the expected one with outcomes showing in exact order Successful, Failed,Cancelled order.
    
  In Delierables 2 , I wanted to create a single query which could apply for the subsequent rows, but each row had differnt criteria with outcomes 'Successful','Failed','Canceled' respectively for each.so, I created a single query with fixed data range(selecting F4 for data range) and just modified the outcome criteria for each columns in the row.
   

## **Results**

- **What are two conclusions you can draw about the Outcomes based on Launch Date?**
    * The spikes on the line graph which hapened between Jan - Feb, Mar - Apr, Apr - May were essentailly most successful moth for the campaign
    * There are more successful outcomes based on Launch date than failed and canceled.
    * The outcomes increased to the peak during the month of May
    * There are very few of them which were cancelled.

#### **Theater Outcomes based on Launch Date**
![img](https://github.com/hsurisetti/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

#### **Outcomes based on Goals**
![img](https://github.com/hsurisetti/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

- **What can you conclude about the Outcomes based on Goals?**
  
   * Percentage canceled were the least in outcomes based on Goals
   * The percentage of outcomes were successful started out good for lesser outcomes , but fell drastically after 40,000 goal amounts
   * The failed outcomes increased drastically after 40,000 goal amount.

- **What are some limitations of this dataset?**
   * Some of the limitations that I observed is that, there is no error control . It is very difficult to find errors in Excel. Also, I didnt notice any debugging tool or testing framework to inspect whether all cells kept working as expected . Some of them were fixable like DIV/0 where I used iFERROR to check if there are any errors.
   * Since we are dealing with large data set , scalability is often a concern.
   * Sometimes the speed and performs degrades when running operations of big data sets but didnt notice any crashes so far.
   

- **What are some other possible tables and/or graphs that we could create?**
     We could also created clustered bar charts, stacked barcharts, different 2D and 3D line and bar charts, histograms.
     
