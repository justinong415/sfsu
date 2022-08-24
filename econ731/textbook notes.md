
1. [The Nature of Econometrics and Economic Data](#The-Nature-of-Econometrics-and-Economic-Data)
   1. [What is Econometrics](#What-is-Econometrics)
   2. [Steps in Empirical Economic Analysis](#Steps-in-Empirical-Economic-Analysis)
   3. [Structure of Economic Data](#Structure-of-Economic-Data)

## The Nature of Econometrics and Economic Data

### What is Econometrics?

1. Econometrics is based upon the development of statistical methods for:
   1. estimating economic relationships
   2. testing economic theories
   3. evaluating and implementing government and business policy
2. Difference between Econometrics and Mathematical Statistics:
   - Econometrics focuses on problems inherent in collecting and analyzing nonexperimental economic data.
     - Nonexperimental data are not accumulated through controlled experiments on individuals, firms, or segments of the economy. 
     - Nonexperimental data are sometimes called observational data, or retrospective data, to emphasize the fact that the researcher is a passive collector of the data.
   - Experimental data are often collected in laboratory environments in the natural sciences, but they are more difficult to obtain in the social sciences.

### Steps in Empirical Economic Analysis

1. Empirical analysis: A study that uses data in a formal econometric analysis to test a theory, estimate a relationship, or determine the effectiveness of a policy.
2. Structuring an empirical economic analysis first requires careful formulation of the question of interest.
3. Economic model: Mathematical equations that describe various relationships derived from economic theory or less formal economic reasoning.
4. Utility maximization: The basic premise underlying economic models; leads to a set of demand equations.
   - Individuals make choices to maximize their well-being, subject to resource constraints, gives a framework for creating tractable economic models and making clear predictions.
5. Demand equation: the quantity demanded of each commodity depends on the price of the goods, the price of substitute and complementary goods, the consumer’s income, and the individual’s characteristics that affect taste.

<details>
  <summary>Example: Economic Model of Crime</summary>

   1. Gary Becker postulated a utility maximization framework to describe an individual’s participation in crime. 
   2. Certain crimes have clear economic rewards, but most criminal behaviors have costs. 
   3. The opportunity costs of crime prevent the criminal from participating in other activities such as legal employment.
   4. In addition, there are costs associated with the possibility of being caught and then, if convicted, the costs associated with incarceration. 
   5. The decision to undertake illegal activity is one of resource allocation, with the benefits and costs of competing activities taken into account.

   Under general assumptions, we can derive an equation describing the amount of time spent in criminal activity as a function of various factors. We might represent such a function as

   $$ y = f(x_1, x_2, x_3, x_4, x_5, x_6, x_7) $$
   
   - $y$ =  hours spent in criminal activities
   - $x_1$ = "wage" for an hour spent in criminal activity
   - $x_2$ = hourly wage in legal employment
   - $x_3$ = income other than from crime or employment
   - $x_4$ = probability of getting caught
   - $x_5$ = probability of being convicted if caught
   - $x_6$ = expected sentence if convicted
   - $x_7$ = age
   
</details>


<details>
  <summary>Example: Job Training and Worker Productivity</summary>

   $$ wage = f(educ, exper, training) $$
   
   - $wage$ = hourly wage
   - $educ$ = years of formal education
   - $exper$ = years of workforce experience
   - $training$ = weeks spent in job training
   
</details>

1. **Econometric model**: An equation relating the dependent variable to a set of explanatory variables and unobserved disturbances, where unknown population parameters determine the ceteris paribus ("other things equal") effect of each explanatory variable.
2. The form of the function $f(·)$ must be specified for an econometric model to relate to an economic model.
3. Some variables cannot reasonably be observed or even list, but we must somehow account for them.
   - Example: wage earned in criminal activity. Difficult to realistically observe, but we can observe relevant arrest statistics and derive a variable that approximates the probability of arrest.

Ambiguities inherent in economoc model of crime are resolved by specifying a econometric model:

$$ crime = \beta_0 + \beta_1wage + \beta_3freqarr + \beta_4freqconv + \beta_5avgsen + \beta_6age + u $$

 - $crime$ = some measure of the frequency of criminal activity
 - $wage$ = the wage that can be earned in legal employment
 - $othinc$ = the income from other sources (assets, inheritance, and so on)
 - $freqarr$ = the frequency of arrest for prior infractions
 - $freqconv$ = the frequency of conviction
 - $avgsen$ = the average sentence lenfth after conviction
 - $u$ = unobserved factors, such as wage for criminal activity, moral character, family background, and errors in measuring things like criminal acivity and probability of arrest

The constants $\beta_0$ , $\beta_1$, ..., $\beta_\beta$ are the paramters of the econometric model. 
 - They describe the directions and strengths of the relationship between crime and factors used to determine _crime_ in the model.


### Structure of Economic Data

#### Cross-Sectional Data



