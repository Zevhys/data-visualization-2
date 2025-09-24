 # data-visualization-2
![Created](https://img.shields.io/badge/Created-21--Sep--2025-blue.svg) [![Author](http://img.shields.io/badge/author-@Zevhys-blue.svg)](https://www.linkedin.com/in/rakha-djauhari/) [![GitHub license](https://img.shields.io/github/license/Zevhys/data-visualization-1)](https://github.com/Zevhys/data-visualization-1/blob/main/LICENSE) ![GitHub repo size](https://img.shields.io/github/repo-size/Zevhys/data-visualization-1) [![Issues Welcome](https://img.shields.io/badge/issues-welcome-brightgreen.svg)](https://github.com/Zevhys/data-visualization-1/issues) [![Pull Requests Welcome](https://img.shields.io/badge/pull%20requests-welcome-brightgreen.svg)](https://github.com/Zevhys/data-visualization-1/pulls)

<div align="center">
<img src="Thumbnail.webp" height="350px"> 
</div>

</br>

# Project Overview 📄
This project is a comprehensive analysis of a credit card customer, presented as an interactive dashboard. The primary goal is to transform raw customer and transaction data into actionable insights, helping stakeholders understand the customer base, identify revenue streams, and assess credit risk. This project serves as a practical demonstration of data visualization and business intelligence skills, showcasing how to effectively communicate complex data stories.

# Key Analyses & Visualizations 📊
- Customer Segmentation: </br>
A detailed breakdown of the customer base by key demographic segments, including Occupation and Education Level.

- Geographic Risk Analysis: </br>
A ranked view of states with the highest Delinquent Account Rates, allowing for targeted risk management.

- Revenue & Performance Metrics: </br>
Tracks high-level KPIs such as Total Revenue, Active Customers, and the overall number of delinquent accounts.

- Performance Over Time: </br>
An interactive time-series chart to monitor trends in key metrics.

# Tech Stack 🛠️
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat-square&logo=google-sheets&logoColor=white)
![diagrams.net](https://img.shields.io/badge/diagrams.net-F08705?style=flat-square&logo=diagramsdotnet&logoColor=white)
![Google Looker Studio](https://img.shields.io/badge/Google%20Looker%20Studio-4285F4?style=flat-square&logo=looker&logoColor=white)

# Requirements ✅
This guide will walk you through the steps to build this dashboard from scratch using the provided dummy data.

### Step 1: Design the Dashboard Mockup
Before creating the actual data visualization report, create a mockup/wireframe to define the layout, charts, and key metrics you want to display.

<pre>
- Use a diagramming/wireframing tool such as <a href="https://app.diagrams.net/" target="_blank">diagrams.net</a> or alternatives like Figma/Excalidraw.

- Include the intended KPIs (e.g., total revenue, orders), chart types (e.g., time series, bar, pie), filters (e.g., date range, category), and overall layout.

- Export or save the mockup (PNG/PDF) so you can reference it while building the report.
</pre>

### Step 2: Prepare the Data Source assets
First, you need to get the data into a format that Looker Studio can easily connect to. We'll use Google Sheets for this.

<pre>
- Download the <a href="assets/Dataset.csv">Dataset.csv</a> file from this repository.

- Go to <a href="https://sheets.google.com" target="_blank">Google Sheets</a> and create a new blank spreadsheet.

- In the new spreadsheet, go to File > Import.

- Select the Upload tab and choose the .csv file you just downloaded. Leave the import options as default and click Import data.

- Rename the spreadsheet to something descriptive, like "E-commerce Sales Dashboard Data".
</pre>

### Step 3: Connect Looker Studio to Your Data
Now, let's connect our new Google Sheet to a Looker Studio report.

<pre>
- Go to <a href="https://lookerstudio.google.com" target="_blank">Looker Studio</a> and click on Blank Report.

- You will be prompted to add data to the report. In the list of connectors, select Google Sheets.

- Find and select the spreadsheet you just created ("E-commerce Sales Dashboard Data").

- Ensure the correct worksheet is selected and click the Add button in the bottom right corner.
</pre>

### Step 4: Build the Visualizations 
You are now ready to build the dashboard! You have a blank canvas and all the data fields available in the panel on the right.

<pre>
- Use the PDF Preview: Refer to the Report <a href="assets/Report Preview.pdf">Report Preview.pdf</a> file in this repository as your guide. It shows you what charts to build and what metrics/dimensions to use.

- Add Charts: Click on Add a chart from the toolbar and select the appropriate chart type (e.g., Scorecard, Time series chart, Bar chart, Pie chart).

- Configure Charts: For each chart, drag and drop the fields from the right-hand panel into the Dimension and Metric sections. For example, for a "Revenue by Category" bar chart:
 · Dimension: category
 · Metric: revenue (or the relevant price/amount field)

- Style Your Dashboard: Use the Style tab for each chart to change colors, fonts, and labels to match the preview.
</pre>
# Contribution 🤝
Contributions are welcome! If you have suggestions for improvements or want to report an issue, feel free to open a pull request or create an issue. Thank you for helping to make this project better!
