# House-Price-Prediction

Import tools → We bring in Python libraries to work with tables (Pandas), make graphs (Seaborn, Matplotlib), and build models (Scikit-Learn).

Load dataset → Use fetch_california_housing() to get a built-in housing price dataset from Scikit-Learn.

See first rows → df.head() shows the first few rows so we know what data looks like.

Check info & stats → df.info() tells us data types, df.describe() gives numbers like average, min, max.

Plot target values → Draw a histogram of MedHouseVal (house price) to see price distribution.

Group by income → Create bins for income (VeryLow → VeryHigh) and see average price in each group.

Plot group averages → Bar chart shows how house prices rise with income level.

Pick features → Choose important numeric columns like income, house age, rooms, etc.

Split data → 80% for training, 20% for testing so we can check accuracy later.

Train model → Use Linear Regression to learn the relationship between features and house price.

Make predictions → Use the trained model to guess prices for the test set.

Compare results → Table shows actual vs predicted prices (first 10 rows).

Scatter plot → Plot actual vs predicted points; a perfect model would be on the red line.

Check errors → Calculate residuals (actual − predicted) to see how far off the guesses are.

Plot errors → Histogram of residuals shows how errors are spread (good models have small errors around zero).
