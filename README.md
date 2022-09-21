My mission here for the french organization <i>ONCFM (National Anti-Counterfeiting Organization)</i> is to set up an algorithm that will automatically identify counterfeit euro banknotes based on their dimensions and elements that compose them.<br>
<br>
 
<strong>Summary</strong> :

    
 <strong>Tools </strong>
 
  <strong>I. Exploratory data analysis</strong><br>
     -- A. Dataset description<br>
     -- B. Treatment of missing values using linear regression to predict them<br>
     ---- <i>a. Linear regression (statsmodel)</i><br>
     ---- <i>b. Results analysis</i><br>
     <i>------ → Calculation of levers</i><br>
     <i>------ → Calculation of studentized residuals</i><br>
     <i>------ → Cook's Distance calculation</i><br>
     <i>------ → Testing the collinearity of variables</i><br>
     <i>------ → Testing homoscedasticity</i><br>
     <i>------ → Testing residual normality</i><br>
     ---- <i>c. Prediction and imputation of missing values</i>    
     -- C. Principal component analysis (PCA) on features<br>
     ---- <i>a. Data standardization</i><br>
     ---- <i>b. Explained Variance Ratio and Scree plot</i><br>
     ---- <i>c. Correlation circles and projections of points</i><br>
     -- D. Univariate analysis on target<br>
     <br>
  <strong>II. K-means clustering</strong><br>
     -- A. Finding the optimal number of clusters for classification (Elbow method)</i><br>
     -- B. K-means model<br> 
     -- C. Factorial plane<br>
     -- D. Centroid analysis<br>
     <br>
  <strong>III. Logistic regression</strong><br>
  <br>
  <strong>IV. Comparison of the two models and implementation of the function</strong><br>


