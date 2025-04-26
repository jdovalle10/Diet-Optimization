# Diet Optimization – Data Science Project

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![Optimization](https://img.shields.io/badge/Optimization-Dietary%20Planning-brightgreen)
![Linear Programming](https://img.shields.io/badge/Linear%20Programming-Nutrition%20%26%20Cost-orange)
![Data Science](https://img.shields.io/badge/Data%20Science-EDA%20%7C%20Feature%20Engineering-lightgrey)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## Table of Contents
- [Overview](#overview)
- [Data Description](#data-description)
- [Conclusions](#conclusions)

---

## Overview
This project presents a simplified yet extensible model to assist individuals in designing an optimal meal plan aligned with their budget, dietary preferences, and fitness goals. User preferences may prioritize different objectives, such as minimizing environmental impacts (e.g., CO₂ emissions and water usage) or maximizing specific nutritional intakes like protein. 

While individual dietary needs are inherently diverse, the framework developed here offers a flexible and scalable foundation for personalized meal planning. Future extensions can seamlessly integrate additional dietary, health, or sustainability goals, enhancing the tool's adaptability and real-world application.

## Data Description
The dataset was sourced from the U.S. Department of Agriculture and includes dish names along with detailed macronutrient and micronutrient profiles. To enrich the dataset:
- **Categorical Enrichment:** Flags were added to classify whether a dish is vegetarian and whether it is appropriate for breakfast, lunch, or dinner, based on its category and keyword analysis.
- **Cost Information:** Dish prices were assigned in CAD, reflecting average market prices in Montreal (2024). Cost ratios across categories were reviewed and adjusted to ensure consistency and plausibility.
- **Environmental Impact Metrics:** Estimated CO₂ footprints and water usage figures were assigned based on ingredient-level analyses using Generative AI models. These estimates were validated against known category benchmarks to ensure logical and reliable values.

This enhanced dataset provides a comprehensive foundation for dietary optimization, combining nutrition, cost, and sustainability considerations.

## Conclusions
- **Trade-offs Identified:** The optimization model highlighted inherent trade-offs between nutrition-focused and sustainability-focused meal plans. This version emphasized protein as the primary macronutrient; future iterations should incorporate a more balanced approach, including fats, carbohydrates, and essential micronutrients.
  
- **Scalability Opportunities:** Expanding the dataset with broader environmental impact data would strengthen the sustainability analysis, offering a deeper understanding of the trade-offs in dietary choices and aligning the tool with global health and sustainability goals.

- **Business Potential:** The project showcases significant commercial applications. Potential opportunities include partnerships with fitness companies, grocery delivery services, and corporate wellness programs. Business models could range from personalized, subscription-based meal plans to eco-labeling services and integrated wellness platforms that combine nutrition planning with convenience and environmental consciousness.

---


