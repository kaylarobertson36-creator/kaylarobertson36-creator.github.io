# Nutritional Inequality and the Case for Transparent Health Scoring: A Computational Social Justice Analysis

**Kayla Robertson | Howard University | MS Applied Data Science and Analytics**

## Introduction

Access to nutritious food in the United States is not distributed equally. For millions of low-income Americans and communities of color, the foods available in their neighborhoods are not the foods that support long-term health. This is not a matter of personal preference or even habits that are formed culturally, but the result of decades of policy decisions, corporate marketing strategies, and systemic disinvestment that have created and maintained what researchers call food deserts. The nutritional divide in this country is a measurable form of systemic inequality, and the Health Impact Score developed in this capstone project provides evidence of that divide. More importantly, it offers a practical alternative to the confusion of nutrition labels and endless online searches: a single, universal score that makes understanding food quality accessible to everyone, not just those with the time and background to decode it.

## The Problem Statement: Who Is Being Left Behind and Why

The United States Department of Agriculture defines a food desert as a low-income census tract where a substantial share of residents live more than one mile from a supermarket in urban areas, or more than ten miles in rural areas. According to the USDA Economic Research Service, approximately 19 million Americans live under these conditions, with Black and Hispanic communities disproportionately represented (USDA ERS, 2021). Research published in the American Journal of Preventive Medicine found that even when grocery stores exist in low-income neighborhoods, their shelves carry significantly fewer fresh fruits, vegetables, and whole grain products than stores in higher-income areas (Larson, Story, and Nelson, 2009). Residents of underserved communities are not simply making different food choices but choosing from a smaller set of options.

Compounding this problem is the role of targeted food marketing. A report from the Rudd Center for Food Policy and Health found that Black youth are exposed to 70 percent more food and beverage advertisements than white youth, with the vast majority of those advertisements promoting products high in sugar, saturated fat, and sodium (Harris, Frazier, Kumanyika, and Ramirez, 2019). The health consequences are well documented. Black Americans are 30 percent more likely to die from heart disease than white Americans and are nearly twice as likely to be diagnosed with Type 2 diabetes (CDC, 2023). These disparities are not explained by genetics but are predictable outcomes of living in environments where the most available and most affordable foods are the most nutritionally harmful.

Beyond access and marketing, there is a third barrier that receives far less attention: health literacy. The ability to read and meaningfully interpret a nutrition label requires a working understanding of daily value percentages, serving sizes, and nutrient terminology that is not universally taught or accessible. The National Assessment of Adult Literacy found that only 12 percent of American adults have proficient health literacy, with significantly lower rates among low-income adults and communities of color (Kutner, Greenberg, Jin, and Paulsen, 2006). For a parent standing in a grocery store trying to decide between two products, a label listing 38 grams of total carbohydrates with 12 grams of added sugars provides little actionable guidance without the context to interpret it. This is precisely the gap the Health Impact Score is designed to fill. A single number between 0 and 1 requires no nutritional background to understand.

## Connecting the Analysis: What the Data Shows

The Health Impact Score assigns each of 7,500 foods from the USDA FoodData Central database a score between 0 and 1, rewarding dietary fiber, Vitamin C, potassium, protein, magnesium, and calcium, while penalizing sugars, saturated fats, cholesterol, and sodium. The results reveal a stark divide. The top-scoring foods include spinach (0.97), kale (0.94), lentils (0.85), and black beans (0.83), foods that are nutritionally exceptional but among the least available in food desert environments. The bottom-scoring foods include glazed donuts (0.11), hot dogs (0.13), and cheese puffs (0.10), precisely the products that dominate corner stores and fast food outlets in underserved communities.

The statistical analysis confirmed the significance of this gap. A Pearson correlation test found a statistically significant positive relationship between dietary fiber and Health Impact Score (r = 0.76, p < 0.05). A T-test comparing the health scores of the top 10 percent of fiber-rich foods against the bottom 10 percent produced a t-statistic of 9.88 and a p-value approaching zero, indicating the nutritional difference between these groups is large and not due to chance. The Random Forest model identified potassium as the single strongest predictor of food quality, with an importance score of 0.81. Potassium deficiency is linked to hypertension and cardiovascular disease, conditions that disproportionately affect Black Americans, and the foods most available in underserved communities are consistently the lowest in this nutrient.

It must also be acknowledged that the USDA dataset has real limitations. It captures nutrient content but not geographic availability, price, or preparation burden. A food that scores 0.97 is of limited value to a family in a neighborhood where it is not sold or costs three times as much as the processed alternative. These gaps do not discredit the analysis, but they make clear that nutritional data alone cannot capture the full reality of food insecurity.

## Advocacy and Recommendations

The evidence supports intervention at multiple levels. For policymakers, expanding SNAP incentive programs such as Double Up Food Bucks, which match SNAP spending on fresh produce dollar for dollar, and implementing zoning policies that limit fast food density near schools while incentivizing full-service grocery stores in food deserts, would address the structural root of the problem. The Health Impact Score methodology could be adapted as a transparent, public-facing evaluation tool for SNAP-eligible products. For the food industry, Federal Trade Commission authority must regulate predatory food marketing directed at children and communities of color. And for data scientists, tools like the Health Impact Score should be integrated into the platforms low-income consumers actually use, including grocery apps and SNAP EBT systems, so that a transparent, easy-to-read score reaches the people who need it most.

## Conclusion

Type 2 diabetes, hypertension, and cardiovascular disease are not simply medical diagnoses. They are the compounding outcomes of a food system that has placed profit above public health and convenience above equity. The Health Impact Score cannot by itself reverse decades of disinvestment or undo the chronic disease burden that structural food inequality has produced. What it can do is make the nutritional divide visible, measurable, and harder to ignore.

## References

Centers for Disease Control and Prevention. (2023). *Health disparities in cardiovascular disease.* Retrieved from https://www.cdc.gov/heartdisease/disparities.htm

Harris, J.L., Frazier, W., Kumanyika, S., and Ramirez, A.G. (2019). *Increasing disparities in unhealthy food advertising targeted to Hispanic and Black youth.* Rudd Center for Food Policy and Health, University of Connecticut.

Kutner, M., Greenberg, E., Jin, Y., and Paulsen, C. (2006). *The Health Literacy of America's Adults: Results from the 2003 National Assessment of Adult Literacy.* U.S. Department of Education, National Center for Education Statistics.

Larson, N.I., Story, M.T., and Nelson, M.C. (2009). Neighborhood environments: Disparities in access to healthy foods in the U.S. *American Journal of Preventive Medicine,* 36(1), 74-81.

U.S. Department of Agriculture Economic Research Service. (2021). *Food Access Research Atlas.* Retrieved from https://www.ers.usda.gov/data-products/food-access-research-atlas/
