# Insurance-Premium-Prediction-Using-Machine-Learning
Supervised Machine Learning Project carried out by a skilled Data Scientist to help an Insurance Company determine the insurance premium to be charged each of their customers based on their individual demographic and lifestyle factors. 

<img width="1833" height="1010" alt="Screenshot 2026-03-31 233422" src="https://github.com/user-attachments/assets/e85ea216-aad2-4470-bd9b-405841193858" />












Five features influencing the predicted charges are Smoking, BMI, Age, Children, and Geographical Region. From the analysis, 'Smoking' was identified to be the 'Dominant Factor' otherwise ranked first at the Feature Importance, with the highest coefficient of +23077.76. This indicates that being a smoker dramatically increases predicted insurance charges compared to being a non-smoker, holding all other factors constant. This is a critical insight, highlighting smoking as the strongest predictor of high premiums in this model.

The Baseline for the insurance charge is $8,643.81. This means that, holding all other factors constant, every customers's charge begins from $8,643.81
Age and BMI showed to be Strong Predictors: They have substantial positive impacts on the insurance charges, consistent with health-related risk factors.
For the Geographical Region, the baseline is set to be Northeast. It is observed that customers who live in the region_sotheast pay the lowest insurance charge with a negative coefficient of -838.92 dollars

Recommendation: Different models and scalers were used (Linear Regression, Ridge, RobustScaler and StandardScaler) in determining how much a customer should be charged for their insurance premium. The company is advised to deploy Linear Regression Model and RobustScaler because of their optimum performance over others. 
