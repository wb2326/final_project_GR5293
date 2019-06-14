# final_project_GR5293

source of data: https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j

General Structure:

1. Introduction

2. Description of the data source

3. description of data import, cleaning and transformation

  removed missing values
  combined data for the same restaurant and kept the most recent record only (for exploring restaurant genres)
  selected a few chain restaurants and investigated its sanity grades
  
4. Analysis of missing values
    EDAV 24
5. results
  Two parts:
    1. Restaurant genre analysis
      
      1.1 count of restaurant of different genre
      
      1.2 zip plot

    2. Violation analysis
      
       2.1 Top 10 violation reason
       
       2.1.1 Violation reason by borough
      
      2.2 Grade to score (use percentage of A) 
        
        2.2.1 zip plot on A%
        
        2.2.2 ridgeline plot on top 10 restaurant genre and socre(0~98)
              score range: 0-13:A, 14-27:B, 28+:C
      
      2.3 Seperate inspection date by month
        
        2.3.1 top violation type by month (group violation code by numeric part)
              
              02: Food temperature
              
              03: Raw material
              
              04: Food preparation & storage/ rats and fly (KLMNO)
              
              05: Facilities 
              
              06: Hygiene
              
              07: Interfering duty
              
              08: Vermin
              
              09: 04
              
              10: Dining environment
        
        2.3.2 top restaurant genres' grade change by month


6. Interactive component

7. Conclusion

Bonus: word cloud, etc
