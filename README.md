# Power-BI-tasks
Tasks done during course learning

**Company Data Analysis using Power BI**
**Project Overview**
This project demonstrates an end-to-end data analysis workflow using Microsoft Power BI. It covers data preparation in Power Query, integration of sales and returns data, data modelling, DAX calculations, report development, and interactive dashboard features.
The project was completed as a series of 20 coursework tasks, progressing from data preparation and model validation to dashboards, navigation, bookmarks, and What-If parameters.
**Objectives**
- Prepare and clean sales, returns, and lookup data.
- Integrate fact tables with product, calendar, and territory dimensions.
- Build and validate a Star Schema data model.
- Create DAX measures for sales, quantities, returns, and performance analysis.
- Analyse trends, products, categories, territories, and geographic performance.
- Develop interactive Power BI report pages.
- Apply bookmarks, page navigation, drill-through, and What-If parameters.
**Tools and Technologies**
- Microsoft Power BI Desktop
- Power Query -- data cleaning, transformation, merging, and validation
- DAX -- measures and analytical calculations
- Microsoft Excel / CSV -- source data
- GitHub -- project versioning and portfolio presentation Data Model
The model uses sales and returns fact tables with shared dimension tables.
**Fact tables**
- Fact_Sales
- Fact_Returns
**Dimension and lookup tables**
- Dim_Product
- Dim_Calendar
- Dim_Territory
- Supporting product category and subcategory lookup data, where applicable
The model uses dimension-to-fact relationships to support filtering and analysis. Relationship cardinality, filter direction, active/inactive relationships, and the absence of direct fact-to-fact relationships were included in the modelling validation work.
**Tasks 1--20: Project Workflow**
The coursework was completed progressively. The following summary describes the main work covered across the 20 tasks.
**Tasks 1--2: Data preparation and Power Query**
- Imported the supplied sales, returns, and lookup data.
- Prepared source queries for analysis.
- Reviewed column names, data types, and data quality.
- Applied relevant cleaning and transformation steps in Power Query.
**Task 3: Returns Analysis & Territory Integration**
- Prepared Fact_Returns and supporting product, category, subcategory, territory, and calendar lookup data.
- Integrated lookup information using the relevant keys and date fields.
- Prepared return quantity and return-date fields for analysis.
- Worked on return quantity summaries, high/low return classification, and category, territory, continent, and year analysis.
**Task 4: Data Integration Check**
- Merged Fact_Sales with Dim_Product using ProductKey.
- Merged Fact_Sales with Dim_Calendar using OrderDate and the calendar date field.
- Checked for duplicate records and validated data types after merging.
- Used the sales fact table's OrderQuantity for product-category and year-wise quantity analysis.
**Task 5: Relationship Behavior & Model Stress Testing**
- Reviewed active relationships in the model.
- Tested an active/inactive calendar relationship and observed its impact on a Year-versus-quantity visual.
- Restored the relationship to Active after testing.
- Reviewed one-to-many / many-to-one cardinality.
- Confirmed that sales and returns are connected through shared dimensions rather than a direct fact-to-fact relationship.
- Tested filter flow, bidirectional filtering, and model ambiguity.
- Hid technical keys and columns from Report view where appropriate.
**Tasks 6--12: DAX, calculations, and analytical reporting**
- Developed DAX calculations and measures for sales and returns analysis.
- Used measures in report visuals and analytical comparisons.
- Worked with filter context and time-based analysis.
- Applied calculations to compare performance across products, categories, dates, and territories.
- Validated report results against the underlying data and coursework requirements.
**Task 13: Executive Dashboard**
- Created an executive-level overview page.
- Presented key performance indicators and sales/returns information in a consolidated layout.
**Task 14: Sales Trend & Forecast Analysis**
- Created the Sales Trend Analysis page.
- Built a line chart using calendar month and sales quantity/value information as required by the task.
- Used Year for comparison and explored trend and forecast options.
- Applied month sorting and chart formatting.
**Task 15: Sales Performance Dashboard**
- Created a dedicated sales performance report page.
- Presented sales performance using KPI and category-level visuals.
**Task 16: Top-N Performance Dashboard**
- Created a Top-N report page.
- Compared product performance using sales and quantity measures.
- Used a Top-N filter to identify leading products.
**Task 17: Advanced Interactive Dashboard**
- Developed interactive report functionality using Power BI visuals and controls.
**Tasks 18--19: Additional report analysis and interactive features**
- Extended the report with geographic, product, customer, and drill-through analysis.
- The PBIX includes supporting report pages and features such as Geographic Sales Dashboard, Product details, Product Page, Drill-through Summary Dashboard, Customer Details, and a custom tooltip page.
- Additional analytical pages include Decomposition Tree and Key Influencer analysis.
**Task 20: Bookmarks, Navigation & Parameters**
- Created the Interactive Control Dashboard page.
- Added Year, Product Category Name, and Region slicers.
- Grouped the slicers into PANEL_Slicers.
- Created Show Filters and Hide Filters bookmarks to control panel visibility.
- Added Show and Hide buttons linked to the corresponding bookmarks.
- Added Summary and Detail page-navigation buttons.
- Created a Sales Target What-If parameter.
- Used the parameter in a gauge and a Target Status card.
- Created a bar chart with an X-axis constant reference line.
- Tested the slicer panel, buttons, and parameter interaction.
**Report Pages**
The uploaded PBIX contains report pages including:
- Executive Dashboard
- Sales Trend Analysis
- Sales Performance Dashboard
- Top-N Performance Dashboard
- Advanced Interactive Dashboard
- Geographic Sales Dashboard
- Drill-through Summary Dashboard
- Product details / Product Page
- Customer Details
- Interactive Control Dashboard
- Decomposition Tree
- Key Influencer
- Custom ToolTip
Some additional learning and supporting pages are also present in the PBIX.
**Key Power BI Features Used**
- Power Query transformations and merge operations
- Fact and dimension table modelling
- Relationship cardinality and filter direction
- Active and inactive relationships
- DAX measures and calculated logic
- KPI and gauge visuals
- Bar, column, line, and geographic visuals
- Top-N analysis
- Slicers and cross-filtering
- Drill-through pages and tooltips
- Bookmarks and button actions
- What-If parameter and dynamic target status Project Files
**Skills Demonstrated**
- Data cleaning and transformation
- Data integration and validation
- Data modelling and relationship management
- DAX calculations
- Sales and returns analysis
- Time-based and trend analysis
- Product and geographic analysis
- Dashboard design and data visualization
- Interactive reporting and navigation
- Analytical thinking and problem-solving
**Conclusion**
This project provided practical experience in using Power BI to transform raw business data into structured analytical reports. It demonstrates the workflow from data preparation and modelling through DAX calculations, dashboard development, and interactive report features.
**Project**: Company Data Analysis using Power BI
**Tool**: Microsoft Power BI Desktop
**Coursework**: Tasks 1--20
