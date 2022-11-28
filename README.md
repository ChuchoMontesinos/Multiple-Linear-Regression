# Multiple Linear Regression

Using the data from `happy.csv`  and a multiple linear regression I predicted the *Happiness Score* using the features *Economy*, *Family*, *Health*, and *Freedom* where the general model is 

$$
\hat{y}\left({x}_{1},{x}_{2},{x}_{3},{x}_{4}\right)={\theta}_{0}+\sum_{i=1}^{4}\left({x}_{i}{\theta}_{i}\right)
$$

Doing the analysis I get that `Freedom`  has more weight in out prediction then we can conclude that ${\theta}_{4}$, the parameter for *freedom* has more influence in our model 

Here I used the libraries 
* `Scikit Learn`
* `Pandas`
* `Seaborn`