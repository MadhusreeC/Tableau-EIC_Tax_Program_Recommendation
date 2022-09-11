# Recommendation of Earned Income Credit tax program using Tableau
 This project is done for **Simplify CT/ SVP Consulting**

**Introduction**: 
Simplify CT provides free tax preparation services to Connecticut's most vulnerable residents, allowing them to qualify for further state and federal assistance. SimplifyCT along with SVP wanted to identify locations in Connecticut, where there are the most need of free of cost tax return preparations for economically weaker communities and offer assistance to those areas. 

**Aim**:
In this project, we analyzed publicly available data from the IRS and US Census Bureau for all the zip codes in Connecticut and identified the zip codes which are in highest need of promotion of the program Earned Income Credit (EIC). 


**Data collection**:
We collected the open source data from the IRS website. It consisted of the  Individual Income Tax Returns, Selected Income and Tax Items by State, ZIP Code, and Size of Adjusted Gross Income for the Tax Year 2019. From this data we got the information of the number of returns in Earned Income credit per zip code for different size bands of adjusted gross income. This data was mainly used for determining the numerator which is the number of households utilizing the benefit of EIC. We also collected the data from the US census Bureau which contained the information about the number of households per income band. This acted as the denominator which has the total number of households which should get the benefit of EIC. The households who qualified for the EIC program should have worked and  earned income under $57,414. So we restricted our income band upto $75,000.

**Methodology**:
For the numerator we aggregated the number of returns per income band per zip code. For the denominator the data had the total population and the percentage per income band. We used excel to calculate the number of households per income band. To collect the common zip codes in both the data sources, we used VLOOKUP in excel. Then we imported the articulated datasource in Tableau and created the interactive map dashboards using Tableau. We have two dashboards, the first one showing the number of households per income band. The second one shows the percentage of households claiming EIC per zip code. Finally we have a recommendation dashboard highlighting the zip codes which are in most need of the benefit of EIC. We also have a contents page in our Tableau dashboard which can be modified later with additional programs. That gives an easy navigation to the dashboard of our interest. 

**Challenges**: 
The main challenge was to get the data source. Also fitting the data in tableau in correct format so that there is no miscalculation was important. We made some mistakes while fitting the data. We had to spotcheck everytime to make sure that the ratios were correctly calculated. 

**Conclusion**: 
We were involved in aggregating data from a variety of public resources, analyzing it to determine social need based on geography, identifying specific geographic areas with the greatest need, determining the current EIC benefit utilization rate, and finally visualizing the data through interactive maps using Tableau. 






