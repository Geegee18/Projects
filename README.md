# Projects
This is a Github repo for projects that I have worked on.


“You can, for example, never foretell what any one man will do, but you can say with precision what an average number will be up to. Individuals vary, but percentages remain constant. So, says the statistician.”  
Sherlock Holmes (The signs of Four)



## Title: Analysis of Pet food label Use. (What consumers look for on such labels).
Summary:
Pet food has become one of the leading food products of very great essence to this generation. Increasing research has shown that there is a need for pet owners to take note of the food they buy for their pets. This has left a question of “What do purchasers really consider from the label the first time they purchase a particular pet food product?”. This study seeks to investigate and answer this question. 
The main objective of the study was to harness most of the information that influences the use of pet food labels using Principal Component Analysis and identify the latent factors that influence it using Factor Analysis. The data for this study was part of the 2008 Health and Diet Survey of the Food and Drug Administration. The data was specifically on pet food label use which would be item K6 in the survey instrument. The study showed that the first two principal components accounted for 72% of the variation in the data gotten from the survey.  Also, there were two main factors namely economic and content factors that influenced pet food label use. The amount of food per single serving (K6A), how high or low pet food is in nutrients (K6B), whether product meets nutritional needs (K6C) loaded very highly on the content factor while advertising specification (K6E) was influenced by the economic factor.  This information would give advertisers an idea of what to highlight on these labels for subsequent pet food products. This study was done using the SAS statistical software. 
The final submission was a LaTeX presentation slide. 

## Title: A predictive model to ascertain the relationship between spine bone density and other variables in the North American Adolescents Bone data.

Summary:
The aim of this study was to ascertain the relationship between the variables in the bone data and to find the best model to predict the spine bone mineral density. The dataset used was the bone data in the ElemStatlearn package in R. It consisted of measurements in bone mineral density of 261 North American adolescents who made two consecutive visits to the hospital. The data has the average ages over the two visits, gender of the adolescents and the identification number of the individuals to show the repeated measurements. The statistical methods used were linear model, polynomial regression, LASSO regression, generalized additive model and LOESS. The model with least test error was the polynomial regression of degree 4. Age was the only variable that was significant in predicting bone mineral density.
This study was done using the R software. 
Find a link to the study and code below.



## Title: Effects of variables in the SA Heart Data on Coronary Heart Disease (CHD).
Summary: 
In this project, the SAheart data in the ElemStat Learning package in R was explored to determine the relationship between corona heart disease and the other variables in this data set. The other variables in the data set were their systolic blood pressure, total lifetime usage of tobacco in kilograms, the amount of low density lipoprotein cholesterol which is considered bad for health and a prevailing cause of heart disease, adiposity (numeric BMI measure of the weight of the males), whether an individual has a family history of heart disease (a factor with levels Absent Present), a measure of a person’s Type A behavior (how aggressive, impatient and competitive an individual is). People with Type A behavior are known to be prone to chronic heart disease. Obesity, current alcohol consumption, age at onset and coronary heart disease. 
A number of statistical methods such as logistic regression, linear discriminant analysis (LDA), quadratic discriminant analysis, K-Nearest neighbor, decision tree, bagging and random forest were used. It was observed that tobacco intake, low density lipoprotein level and age of an individual were the most important factors in classifying an individual as having CHD or not. The model with the highest kappa value was the LDA method. Overall, most of the models selected tobacco intake, age, the amount of low density lipoprotein cholesterol as the top variables in the classification of CHD. Though family history was important in some models, it did not stand out in most models.
This study was done using the R software. 
Find a link to the study and code below.




## Title: Exploration of MPG dataset
Summary:
In this study, the mpg dataset in R was explored using exploratory data analysis techniques. The main objective was to answer a set of questions pertaining to the data even before any confirmatory analysis was done. Some of the questions were:
What is the typical engine displacement of a car?  Are there any extreme values?
What is the typical engine displacement for each class of car? Is the spread stable, if not is there a transformation that will stabilize the spread? 
What are the most efficient wheel types for within city transport in terms of mpg?
Identify the specific manufacturer and model of car that is unusual in that category.
What is the most efficient four-wheel car for within city transport? 
These questions were answered in the study.
With respect to the data; the typical engine displacement of a car was 3.3L.
 Four-wheel drive, front wheel drive and rear wheel drive has a typical engine displacement of 4L, 2.4 L and 5.4L respectively. A 2-seater car has an average (typical) engine displacement of 6.2 L, compact (2.2 L), midsize(2.8L)), minivan(3.3L)), pickup (4.7 L), subcompact (2.2 L), SUV(4.65L). From the exploration, the most efficient type of wheel for within city driving was a front wheel drive car. Volkswagen New beetle (1999 model) manual transmission was the most efficient within city car in terms of mileage. Dodge Caravan (2008 model) was the least efficient front wheel drive car. Subaru Impreza awd (1999 model) was the most efficient 4 wheel drive for within city movement having an unusual mpg of 2. The most efficient type of wheel for highway driving was also the front wheel car. Volkswagen new beetle (1999) and Volkswagen Jetta was the most efficient FWD car for the highway.
This study was done using the R software. 


## Title: Verification Procedure of the Linear least Squares Solver (Simulation Study) 

Summary:
This project especially highlights my advanced coding skills in R and how I am able to translate a statistical algorithm into a working code. This project partially had me replicate the verification procedure for least squares solvers for specific Zielke matrices.
In this analysis, verification of the LLS solvers based on exactly representable solutions was explored.
The simulation was run for pairs (n=4, k=1), (n=8, k=3), (n=16, k=7), (n=32, k=15) and (n=64, k=31) for m =0 to 20 where z= 2^m. Nonconsecutive rows were deleted to create the Zielke Matrices with different condition numbers. Also, general response vectors with different magnitude of angles between a randomly sampled response and Im(X) were generated. These were used to find the relative errors between the LLS solution and the true parameter values whose exact solution could be found. The simulation was run 100 times for each pair; the relative errors, mean relative errors and the standard deviation of the relative errors of each iterate was stored. Overall, 105 mean relative errors were generated and there were 4 columns of relative errors signifying a very small angle type (err1), medium small angle type (err2), medium large angle type(err3) and the very large angle type (err4).  The results were very true to what was expected in theory. 
Find a link to the presentation slides and code below








![image](https://user-images.githubusercontent.com/89955174/191955319-04076eef-4262-47e5-af5b-455119155ce9.png)
