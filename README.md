# EDA for Retail Company: Tracking Salesperson Performance

## Executive Summary

  The Excellence Retail company operates in locations across the US, using frequent campaigns to sell products from several diverse product categories. Using SQL and Power BI, I pulled transactional data from the database along with corresponding fact tables to analyze our business landscape and understand what is driving our sales and how we can adjust our strategy going forward. I recommend that the marketing team implement a few adjustments that will lead to a more focused approach to optimize sales:

  1.	Identify Generalists vs Specialists in the salesforce
  2.	Use campaign, store location, and product category concentration for each salesperson to refine areas where salespeople should focus their attention
  3.	Create a Salesperson Performance Dashboard to track performance in real-time

## Business Problem

  We would like to examine salesperson performance and use insights to help them continuously improve. How can we guide our salespeople to focus on their strengths and develop into specialists?

## Methodology 

  1.	SQL query that extracts, cleans, and transforms the data from the database.
    
  2.	A cluster analysis using Python that uses salesperson base metrics to create clusters.
     
  3.	A dashboard in Power BI that ranks and tracks the contribution of each location/product category for each salesperson and campaign performance.

## Skills

  SQL: CTEs, Joins, Case, Window functions, Aggregate functions
  
  Power BI: Translation Dax from SQL, writing functions, ETL, calculated columns, data visualization, data modeling
  
  Python: Cluster Analysis (StandardScaler, KMeans)

## Results and Business Recommendation

  Cluster analysis of shows that salespeople are all generalists and there is no meaningful intention to specialize in areas (location, product category, etc.) where they have more success. Most salespeople perform best in their top 1-2 categories (ex. The top salesperson had 13.8% more sales in Groceries than her next highest category Clothing). Building a dashboard including sales distribution for things like location, product category, and campaign allows the company to adjust goals and redirect leads for salespeople in real-time. Given this insight, I recommend:

  1.	At the end of each quarter, consult the dashboard and adjust individual sales goals for areas of strongest performance.
  2.	Construct teams of salespeople with similar strengths to create specialist clusters via periodic cluster analyses. With product category-based teams, the burden of product knowledge is lightened by focusing on fewer products; with location-based teams, building customer relationships is simpler.
  3.	Consult aggregate sales distribution to spot overperformers (for reward) and underperformers (for discipline).

## Next Steps

  1.	Examine salesperson hierarchy and incentive structure to retain top performing salespeople.
  2.	Assess the competitive landscape of highest-grossing locations to decide the best areas to expand.
