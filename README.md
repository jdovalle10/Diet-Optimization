# Diet-Optimization
## Overview
This project proposes a simplified model to assist individuals in designing an optimal meal plan that aligns with their budget, dietary preferences, and physical (fitness) goals. Preferences, in this context, may emphasize either minimizing environmental impacts—such as CO₂ emissions and water usage—or maximizing specific nutritional values, such as protein intake. While individual preferences are inherently diverse, the tools and methodologies introduced here can be expanded to accommodate a broader range of considerations, offering a scalable approach to personalized meal planning.

## Data Description
A dataset of dishes taken from the US Agriculture Department was used; the dataset included dishes names and detailed nutritional values (macronutrients and micronutrients). To enhance the dataset, we added columns that specify whether a dish is vegetarian and whether it is suitable for breakfast, lunch, or dinner, based on its category and keywords in its description.

For cost analysis, we included the prices of all dishes in CAD, based on average costs in Montreal as of 2024. We reviewed the cost ratios across different categories to ensure consistency and made necessary adjustments.

To incorporate environmental impact, we estimated the CO2 footprint and water usage for each dish based on its ingredients (with the help of Generative AI models). We validated these estimates by comparing the average CO2 emissions and water usage across different categories to ensure the data aligns with logical benchmarks. This provided a reliable and well-rounded dataset for analysis.
