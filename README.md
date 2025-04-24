## Excel Projects 
<!-- Microsoft -->
<h2><p align="center">Retail Sales Dataset</p></h2>


### Abstract
Excel was used to analyse multiple datasets and produce answers to multiple queries from sales to grading students tests. Beyond spreadsheet functions, pivot-tables were also used to produce key results. Supplementing this, the leglislation regarding the proper user of data and legality of data handling were also discussed.


### Dataset
- **Source** retail_sales_Master.xlsx (Also available on Kaggle.com)
- **Initial 8 Fields:**
    - 'Transaction ID', Date, 'Customer ID', Gender, Age, 'Product Category', Quantity, 'Price per Unit'
 
### Sales
The table presented consisted of 8 columns and 1000 customer records. To extract any meaningful analysis from this, multiple summary tables were made reflecting commission rates and a breakdown of the various categories vs. gender.
- For each Customer ID, a total sales column was created reflecting the product of Quantity & 'Price per Unit'. Supplementing this, a commission was also calculate for each record via absolute cell referencing
- Additional comulmns for year, month and day were created using the Date column.
- A generation of either: "Young Adult", "Adult" or "Senior" was then ascribed to each customer from the Age column
An additional table was created showcasing for ever Product Category type: The total sales, the quantity of male products sold, the quantity of female products sold and the average sale. The table was then sorted alphabetically by Product Type and Conditional formatting applied to the sales totals.

On a separate sheet, certain Transaction IDs were to be looked at closer. The proposed VLOOKUP() command was replaced in favour of the more modern XLOOKUP() command as the latter can work with, and output arrays. Furthermore, it isn't conditional on the lookup column being to the left of the return value column. Additional basic functions in excel such as COUNTA() and CONCATENATE() were also explored.

### Student test scores
A table containing test scores for 10 students across 3 different subjects was then looked at.
- For each student: the average score across all 3 subjects was then calculated along with the highest score from any 1 subject
- Filtering was then applied to allow the table to be sorted by student name, subject, average score or highest score.
- Conditional formatting was then applied to the average score to give a colour gradient reflective of the student's score.
- In a final column, data validation was applied to allow a 'Yes' or 'No' answer to the to column header 'Does the student require additional support?'







<!--!
[mySQL](assets/google_site_Tableau_carousel_slide08.png)
![mySQL](assets/google_site_Tableau_carousel_slide09.png)(https://www.apple.com/uk/)
![mySQL](assets/google_site_Tableau_carousel_slide10.png)(https://www.apple.com/uk/)
![mySQL](assets/google_site_Tableau_carousel_slide11.png)(https://www.apple.com/uk/)
![mySQL](assets/google_site_Tableau_carousel_slide12_Tableau_desktop_fullscreen.png)(https://www.apple.com/uk/)
-->
     

