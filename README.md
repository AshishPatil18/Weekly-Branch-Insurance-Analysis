# Weekly Branch's Insurance Analysis: Ahmedabad Branch

## Project Overview

This project involves creating a comprehensive dashboard for analyzing insurance performance across various branches, with a focus on the Ahmedabad branch. The dashboard is designed to facilitate discussions between the Corporate team and individual branch heads regarding new and renewal business numbers. The goal is to provide insights into branch performance, identify key trends, and formulate actionable items.

### Project Goals

- **Branch Dashboard**: Develop a dashboard to discuss new and renewal business numbers with each branch.
- **Performance Metrics**: Discuss key performance metrics for each branch.
- **Overall Performance Summary**: Provide a summary of overall branch performance.
- **Detailed Branch Performance**: Offer a detailed breakdown of performance for individual branches.
- **Key Insights and Action Items**: Highlight key insights and recommend action items.
- **Business Summary**: Summarize new business, cross-sell, and renewal business numbers for each branch.

## Dataset Description

The project utilizes the following datasets:

- **Brokerage**: Contains information about clients' policies, including policy details, income, and renewal status.
- **Fees**: Contains data on client-related income transactions, including revenue details and transaction types.
- **Budget**: Details budget allocations for branches and employees, including new roles, cross-sell initiatives, and renewals.
- **Invoice**: Holds information about invoices generated, including transaction details and associated clients.
- **Meeting**: Tracks meetings managed by account executives, including branch associations and attendee details.
- **Opportunity**: Documents details of opportunities managed by account executives, including revenue, stages, and risk information.

## Steps Followed in Creating the Project in Power BI

1. **Data Preparation**:
   - **Data Import**: Import datasets from various sources (Excel, SQL databases, etc.) into Power BI.
   - **Initial Exploration**: Review datasets to understand structure, identify key columns, and assess data quality.

2. **Data Cleaning**:
   - **Handling Missing Values**: Fill or remove missing data as needed.
   - **Removing Duplicates**: Identify and remove duplicate records to ensure data accuracy.
   - **Correcting Inconsistencies**: Standardize data formats and correct any inconsistencies.

3. **Data Transformation**:
   - **Filtering Data**: Apply filters to focus on relevant data subsets.
   - **Creating Calculated Columns**: Develop calculated columns to derive additional insights from existing data.
   - **Creating Measures**: Define measures for complex calculations and aggregations.

4. **Data Modeling**:
   - **Creating Relationships**: Establish relationships between different tables to enable comprehensive analysis.
   - **Building a Data Model**: Develop a data model that integrates various dimensions and measures.
     ![Screenshot (48)](https://github.com/user-attachments/assets/6803c500-bafd-44aa-9058-95238840179c)

5. **Data Visualization**:
   - **Designing Dashboards**: Create and arrange visuals such as charts, tables, and graphs on the dashboard.
   - **Adding Interactivity**: Incorporate slicers, filters, and drill-through capabilities to enhance user interaction.
   - **Customizing Visuals**: Adjust visual properties (colors, labels, etc.) to improve clarity and presentation.

6. **Creating Calculated Measures**:
   - **Example Measure**: Following way I got calculation of each income class (Cross, New and Renewal)
     ```plaintext
     Total_Cross_Brokerage = SUM(Brokerage[Cross Brokerage]),
     Total_Cross_Fees = sum(Fees[Fees Cross]),
     Cross_Achieved = [Total_Cross_Brokerage]+[Total_Cross_Fees]
     ```
     ![Screenshot (47)](https://github.com/user-attachments/assets/18ea8bda-bb19-4f4b-b5b6-a010cfb37031)
   
   - **Advanced Calculations**: Develop additional measures for KPIs and performance metrics.

7. **Incorporating Key Performance Indicators (KPIs)**:
   - **Defining KPIs**: Identify and create visuals that highlight key performance indicators relevant to the project.
   - **Tracking Performance**: Use KPIs to track progress and performance against targets.
      ![Screenshot (53)](https://github.com/user-attachments/assets/bae0c7a1-df00-44a0-8eeb-92a4d1546197)
      ![Screenshot (52)](https://github.com/user-attachments/assets/b6b53ee8-6a89-4626-9b9f-4efaaba21f72)
      ![Screenshot (51)](https://github.com/user-attachments/assets/fa18836b-eee2-4c07-9a0f-680bbb65f50e)

8. **Dashboard Review and Refinement**:
   - **Reviewing Insights**: Ensure that the dashboard provides actionable insights and meets project goals.
   - **Refining Visuals**: Make adjustments based on feedback and usability testing.
   - **Ensuring Accuracy**: Validate data and calculations to ensure accuracy.

9. **Publishing and Sharing**:
   - **Publishing to Power BI Service**: Publish the finalized dashboard to the Power BI Service.
   - **Sharing with Stakeholders**: Share the dashboard with relevant stakeholders, including Corporate team and branch heads.

10. **Documentation**:
    - **Creating Documentation**: Prepare documentation explaining dashboard features, metrics, and data sources.
    - **Providing Training**: Offer training or guidance for users to effectively interpret and use the dashboard.

   ![Dashboard Preview](https://github.com/user-attachments/assets/1f2e8a1e-09f4-4cf8-a15d-360b1535c2f9)

## Conclusion

The analysis and dashboard creation have led to several actionable insights and recommendations:

- **Increase Sales and Retention**: Utilize the insights to develop strategies aimed at increasing sales and improving client retention.
- **Enhance Operational Efficiency**: Identify inefficiencies and areas for improvement to streamline operations and reduce costs.
- **Market Analysis and Adaptation**: Analyze market trends and adapt strategies to better meet client needs and capitalize on opportunities.
- **Expand Product Offerings**: Assess performance data to identify opportunities for expanding product offerings and addressing gaps in the market.
- **Enhance Customer Service**: Use performance metrics and feedback to enhance customer service and satisfaction.

---

For further details or to contribute to the project, please refer to the documentation and contact following mail: ashishap7875@gmail.com
