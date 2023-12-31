# Techionista Holidays Website Business Case

## Objective
The primary goal of this project was to identify areas for improvement and enhance customer satisfaction across Europe by analyzing customer reviews and optimizing the Techionista Holidays website's performance.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Access and Preprocessing](#data-access-and-preprocessing)
3. [Dimension Tables Creation](#dimension-tables-creation)
4. [Page Customization](#page-customization)
5. [Data Visualization](#data-visualization)
7. [Key Influencer Chart](#key-influencer-chart)
8. [Publishing the report to PowerBI Service](#publishing-the-report-to-powerbi-service)


## 1. Project Overview<a name="project-overview"></a>
**Explanation**: This section provides an introduction to the project, its objectives, and its significance. It aims to enhance customer satisfaction across Europe through data analysis and website optimization.

## 2. Data Access and Preprocessing<a name="data-access-and-preprocessing"></a>
**Explanation**: Utilized a shared access key to access the dataset from Azure Blob Storage. The key allowed secure access to the storage account. After gaining access and importing the data to PowerBI desktop, performed data preprocessing, which included splitting columns, handling null values, and changing data types. These steps ensured that the data was clean and ready for analysis.

## 3. Dimension Tables Creation<a name="dimension-tables-creation"></a>
**Explanation**: To facilitate efficient data organization and analysis, created dimension tables for Negative and Positive reviews. I established relationships between dimension and fact tables to form star schema. This structuring enabled insightful analysis and visualization.

![](https://github.com/Javeria-Umer/Report-on-Techionista-Holidays-website/blob/main/Techionista%20holidays%20website-model.png?raw=true)

## 4. Page Customization<a name="page-customization"></a>
**Explanation**: Customizing the report's theme was a crucial step. This was achieved by adjusting color schemes, fonts, and sizes to match the Techionista Holidays branding. Additionally, incorporated navigation buttons, titles, and slicers on respective pages to enhance the user experience.

![](https://github.com/Javeria-Umer/Report-on-Techionista-Holidays-website/blob/main/Techionista%20holidays%20website-home.png?raw=true)

## 5. Data Visualization<a name="data-visualization"></a>
**Explanation**: The data visualization process involved creating an interactive report with different pages. Slicers were added to enable data filtering based on countries, cities, hotels, dates, trip types, traveler types, and nationalities. Various visualizations, such as donut charts, maps, decomposition trees, and the Key Influencer Chart, were employed to convey insights effectively.

![](https://github.com/Javeria-Umer/Report-on-Techionista-Holidays-website/blob/main/Techionista%20holidays%20website-trip.png?raw=true)

<br> <!-- This line creates a gap -->

![](https://github.com/Javeria-Umer/Report-on-Techionista-Holidays-website/blob/main/Techionista%20holidays%20website-review.png?raw=true)


## 6. Key Influencer Chart<a name="key-influencer-chart"></a>
**Explanation**: The Key Influencer Chart was efficiently used to summarize the key reasons for the increase or decrease in reviews. This chart provided valuable insights into customer sentiment and its impact on website performance.

![](https://github.com/Javeria-Umer/Report-on-Techionista-Holidays-website/blob/main/Techionista%20holidays%20website-key%20influencer.png?raw=true)

## 7. Publishing the report to PowerBI Service<a name="publishing-the-report-to-powerbi-service"></a>
**Explanation**: After creating the interactive report, I took it a step further by publishing it to Power BI Service, making it accessible to a broader audience for real-time insights.
Use the following link to access the report:
https://app.powerbi.com/reportEmbed?reportId=fa61d2d9-c1dc-4322-96d4-e5916db72a2b&autoAuth=true&ctid=23828106-3f61-47d7-9e8d-c03d006b795f
