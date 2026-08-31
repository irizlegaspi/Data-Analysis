# Data-Analysis-Journey


#Slicers
File used: 1_3_Slicers.pbix

Load the Excel file DimEmployee.xlsx from Datasets/WWI using the Excel workbook button on the top menu. This is located next to the Get data option.

Note: Ensure you also view Excel files when selecting and accessing the Datasets folder.

Create a relationship between FactSale's Salesperson Key and DimEmployee's Employee Key.
Click Save in the New relationship window that appears without changing any settings.

In the Report view, add a slicer.

Add the Employee field to the slicer.
Change the slicer style by opening the Format your visual pane in the Visualizations pane and selecting the Visual tab.
Expand Slicer settings > Options and set the Style dropdown to "Dropdown" (new slicers may already default to "Dropdown").

Right on! We used the slicer to filter on salesperson, the bar chart to select the year, and the card to interpret the profit made by Taj Shand in 2014. Think about the other possibilities -- filtering on location, price, product type, the list goes on!

<img width="780" height="335" alt="Screenshot 2026-08-31 140504" src="https://github.com/user-attachments/assets/dd9c0bba-70cb-450c-94e0-ace5604db68c" />

<img width="780" height="335" alt="Screenshot 2026-08-31 140504" src="C:\Users\irizl\OneDrive\Desktop\PBI-Slicer.png" />


More Columns

Wide World Importers sells two types of products: chilled and dry. This is recorded in the database because chilled products require a different kind of packaging. To compare these product types, you will add the quantity of products sold that are chilled or dry to the column chart.

If you lost progress, close any open reports and load 1_4_more_columns.pbix from the Exercises folder on the desktop.

Select the Quantity of Items Sold column chart.
Select Total Dry Items and Total Chiller Items in the Data pane.

When does chilled started selling?


Let's add a table to our report with the details of sales transactions. With the interactivity of Power BI, this will allow us to see examples of sales based on our selection.

If you lost progress, close any open reports and load 1_5_table.pbix from the Exercises folder on the desktop.


What is the difference between the "Filtering" and "Drill Down" in PBI
-----------------------------------------------------------------------------

The correct choice is:
"Filtering changes the scope of data across visuals, while drill down explores hierarchical data within a single visual."

This is correct because in Power BI:

Filtering is used to limit or change the data that is displayed across multiple visuals on a report page. When you apply a filter, it affects the data shown in all visuals that use the filtered field, changing the overall scope of the data being analyzed.
Drill down is a feature that allows users to explore data at different levels of a hierarchy within a single visual. For example, you can drill down from year to quarter to month in a sales chart, but this action only affects the specific visual you are interacting with, not the entire report.
The correct answer accurately describes that filtering impacts multiple visuals by changing the data scope, while drill down is about navigating hierarchical data within one visual. The other options either confuse the effects of filtering and drill down or incorrectly describe their functions.



Which feature allows you to explore different levels od data within the same visual without changing the page?

The correct choice is "Drill down." Drill down is a feature that allows you to explore different levels of data within the same visual, such as moving from a summary view to more detailed data, without leaving the current page. This is useful for analyzing hierarchical data, like going from yearly sales to monthly or daily sales within the same chart.

"Filtering" is incorrect because filtering changes which data is displayed, but it does not allow you to navigate through different levels of detail within the same visual. Filtering typically applies to the entire report or visual, rather than enabling interactive exploration of data hierarchies.

Therefore, "Drill down" is the correct answer because it specifically refers to exploring data at multiple levels within a single visual on the same page.


What is NOT a valid filter type in PBI

The correct choice is "Dashboard-level filter" because Power BI does not have a filter type called "Dashboard-level filter." In Power BI, the valid filter types are:

Visual-level filter: Applies filters to a single visual on a report page.
Page-level filter: Applies filters to all visuals on a specific report page.
Report-level filter: Applies filters to all pages and visuals within a report.
While dashboards exist in Power BI, filters cannot be applied at the dashboard level. Filters are only available at the visual, page, and report levels within reports, not dashboards. Therefore, "Dashboard-level filter" is not a valid filter type in Power BI, making it the correct answer to the question.



IN a PBI, you are allowed to adjust a visual such that it does not have any impact by any change in other visualizations. What is this function called in PBI? answer: Edit Interactions


What would be the suitable chart for comparing revenue across different regions? Answer: Bar chart



