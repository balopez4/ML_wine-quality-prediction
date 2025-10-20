# Wine Quality Prediction – Machine Learning

This project performs **data analysis and predictive modeling** on red and white wine datasets using physicochemical parameters such as acidity, alcohol, and residual sugar.  
The goal is to evaluate how well **Decision Tree** and **Random Forest** algorithms can predict wine quality based on these measurable chemical features.

## Datasets
- **White Wine:** [Wine Quality Dataset – White Wine](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)  
- **Red Wine:** [Red Wine Quality Dataset](https://www.kaggle.com/code/nimapourmoradi/red-wine-quality)

## Models Used
- Decision Tree Regressor  
- Random Forest Regressor  

Each model was trained and evaluated using the **Root Mean Squared Error (RMSE)** metric.  
The Random Forest achieved the best performance:
- RMSE ≈ 0.86 for White Wine  
- RMSE ≈ 0.88 for Red Wine  

These results indicate that the model can predict wine quality with an average error of less than one quality point.

## Requirements
All dependencies are listed in the `requirements.txt` file.  
Install them with:
```bash
pip install -r requirements.txt

## Conclusion
The Random Forest model achieved better performance than the Decision Tree, with RMSE values around 0.86 for white wine and 0.88 for red wine. This indicates that the model can predict wine quality with an average error of less than one point, showing good predictive accuracy based on physicochemical features.
