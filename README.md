My mission for the french organization <i>ONCFM (National Anti-Counterfeiting Organization)</i> is to set up an algorithm that will automatically identify counterfeit euro banknotes based on their dimensions and elements that compose them.<br>
<br>
<u>Two methods of prediction</u> are in competition here : 
- a classic <strong>logistic regression</strong> ;
- a <strong>k-means</strong> (of which the centroids will be used to perform the prediction).
<br>

<strong>Summary</strong> :

    
 <strong>Tools </strong>
 
  <strong>I. Exploratory data analysis</strong><br>
     -- A. Dataset description<br>
     -- B. Treatment of missing values using linear regression to predict them<br>
     ---- <i>a. Linear regression (statsmodel)<br>
     ---- b. Results analysis<br>
     ------ → Calculation of levers<br>
     ------ → Calculation of studentized residuals<br>
     ------ → Cook's Distance calculation<br>
     ------ → Testing the collinearity of variables<br>
     ------ → Testing homoscedasticity<br>
     ------ → Testing residual normality<br>
     ---- c. Prediction and imputation of missing values</i>    
     -- C. Principal component analysis (PCA) on features<br>
     ---- <i>a. Data standardization<br>
     ---- b. Explained Variance Ratio and Scree plot<br>
     ---- c. Correlation circles and projections of points</i><br>
     -- D. Univariate analysis on target<br>
     <br>
 <strong>II. K-means clustering</strong><br>
     -- A. Finding the optimal number of clusters for classification (Elbow method)<br>
     -- B. K-means model<br> 
     -- C. Factorial plane<br>
     -- D. Centroid analysis<br>
     -- E. Model evaluation<br>
     <br>
  <strong>III. Logistic regression</strong><br>
     -- A. Implementation<br>
     -- B. Tests<br> 
     -- C. Model evaluation<br>
     ---- <i>a. Confusion matrix<br>
     ---- b. Measurement of classification quality (ROC curve)<br>
          ---- c. Optimisation</i><br>
  <br>
  <strong>IV. Test function implementation</strong><br>
     -- A. Sample preparation<br>
     -- B. Test function implementation<br>
     -- C. Test result<br>
     <br>



