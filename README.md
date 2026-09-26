# MySQL Python Data Analytics Mini-Project
**Author: ShuhanYang**

**Project Type: Database Normalization & Business Intelligence Dashboard**

## Project Overview
This project demonstrates comprehensive data analytics skills through database normalization and business intelligence visualization. Using a retail store dataset, the project transforms raw transactional data into a normalized database structure and creates insightful visualizations for business decision-making.

## Key Objectives
- **Database Normalization**: Transform denormalized retail data into a proper relational database structure
- **Data Optimization**: Achieve significant storage reduction through normalization
- **Business Intelligence**: Create meaningful visualizations for strategic business insights
- **Performance Analysis**: Implement efficient database design with proper indexing and foreign key relationships

## Dataset Description
The project uses a comprehensive retail store dataset containing:
- **Order Information**: Order IDs, dates, shipping details
- **Customer Data**: Customer demographics and segmentation
- **Product Details**: Categories, subcategories, product specifications
- **Geographic Data**: Regional distribution across US states and cities
- **Financial Metrics**: Sales, profit, discount, and quantity data

## Database Schema
### Original Structure
- Raw Data: Single denormalized table with 21 attributes
- Data Points: 209,874 total data points
### Normalized Structure
The database is normalized into 5 optimized tables:
1. `customers` - Customer information and segmentation
2. `locations` - Geographic data with unique location identifiers
3. `products` - Product catalog with categories and subcategories
4. `orders` - Order header information with foreign key relationships
5. `order_items` - Order line items (junction table)

## Entity Relationship Diagram
The project includes a comprehensive ER diagram showing:
- Primary and foreign key relationships
- Table dependencies and constraints
- Optimized data structure for query performance

## Key Visualizations & Insights
### 1. Product Category Analysis
- **Technology Leadership**: Technology category leads with $836K in sales
- **Profit Margin Insights**: Office Supplies shows more stable profitability
- **Strategic Value**: Guides product portfolio optimization
### 2. Regional Performance Dashboard
- **West Region Excellence**: 31.6% of total sales with 14.9% profit margin
- **Geographic Opportunities**: California, New York, and Texas lead in sales
- **Operational Efficiency**: East and West regions show superior profit margins
### 3. Customer Segment Analytics
- **Consumer Dominance**: 51.6% of customers contributing highest sales ($1.16M)
- **Home Office Premium**: Smallest segment (18.7%) with highest average order value ($241)
- **Segmentation Strategy**: Clear behavioral differences require differentiated approaches
### 4. Temporal Analysis
- **Seasonal Patterns**: Clear sales peaks at year-end periods
- **Growth Trajectory**: Significant growth in late 2017
- **Sales-Profit Correlation**: Strong correlation of 0.716 between sales and profit

## Business Intelligence Outcomes
### Strategic Insights
- **Market Focus**: Technology products drive revenue, Office Supplies drive margins
- **Regional Strategy**: West region represents most valuable market
- **Customer Strategy**: Balance consumer volume with home office premium segments
### Operational Benefits
- **Inventory Management**: Data-driven guidance for product allocation
- **Marketing Optimization**: Regional and segment-specific campaign targeting
- **Financial Planning**: Seasonal pattern recognition for cash flow management

## Technologies Used
- Database: MySQL
- Data Processing: Python (pandas, numpy)
- Visualization: Python (matplotlib, seaborn, plotly)
- Documentation: Microsoft Word, Markdown

## Analysis Highlights
### Quantitative Results
- **Sales Performance**: Technology category: $836K, Office Supplies: stable margins
- **Regional Distribution**: West region: 31.6% sales share, 14.9% profit margin
- **Customer Segments**: Consumer: 51.6% of customers, Home Office: $241 average order value
- **Temporal Patterns**: Year-end sales peaks, 0.716 sales-profit correlation
### Strategic Recommendations
- **Product Portfolio**: Balance high-volume technology sales with high-margin office supplies
- **Geographic Expansion**: Focus investment in West region while exploring East region opportunities
- **Customer Acquisition**: Differentiated strategies for consumer volume vs. home office premium segments
---
*This project demonstrates comprehensive data analytics capabilities including database design, normalization, business intelligence, and strategic insight generation.*
