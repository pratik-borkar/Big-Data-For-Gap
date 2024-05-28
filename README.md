# GAP Inc. Creative Directors' Impact Assessment

## Project Overview
This project evaluates the implications of GAP Inc. CEO's decision to dismiss the creative directors across three major brands—Old Navy, GAP, and Banana Republic—to decentralize the creative process and embrace a big data business model. Our analysis spans brand perception, product details, and overall product portfolio to understand the strategic shift's impact.

## Process Flow
The project is structured into three main analysis areas:

1. **Brand Landscape**
2. **Product-level Analysis**
3. **Product Portfolio Analysis**
4. **Regression Analysis for Luxury Brands**

### 1. Brand Landscape
- **Data Source**: Data was scraped from SiteJabber, focusing on customer ratings across various dimensions for GAP Inc. and competitor brands.
- **Methodology**: Ratings for six brands against five attributes were visualized using a radar chart to compare GAP Inc.'s performance against industry standards.

### 2. Product-level Analysis
- **Data Source**: Product details, particularly ratings, were scraped from GAP's and Amazon's websites.
- **Statistical Test**: A t-test was conducted to compare the distribution of ratings. With a t-statistic of 49.03 against a critical value of 1.64 (95% confidence), the null hypothesis that GAP does not outperform Amazon could not be rejected.

### 3. Product Portfolio Analysis
- **Data Source**: Product features from Macy's and GAP's websites were scraped and analyzed.
- **Features Analyzed**: Neckline, Fabric, Sleeve length, Color, Occasion, and Price Range.
- **Objective**: To compare and highlight disparities in the product portfolios of Old Navy and Macy’s.

### 4. Regression Analysis for Luxury Brands
- **Focus**: Analysis shifts to Banana Republic and its competitors.
- **Variables**: Annual Sales, Design Style (Classy/Trendy), and Usage of Big Data (0/1).
- **Outcome**: Regression analysis showed that the use of big data is not a significant factor in sales growth (p-value > 0.05).

## Conclusions
- **Old Navy**: Relies heavily on fast fashion and trends. Data analytics can effectively inform marketing and pricing strategies.
- **GAP**: Balances basics with fashion-forward items. While data helps with basics, its role in driving innovation for trendier items is limited.
- **Banana Republic**: Known for quality and classy designs. A data-driven approach may limit the brand's capacity to develop unique and innovative products.

## Tools and Technologies Used
- Python for web scraping and data analysis
- Statistical analysis performed using SciPy for hypothesis testing
- Data visualization with Matplotlib and Seaborn
