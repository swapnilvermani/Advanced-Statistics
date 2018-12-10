# Advanced-Statistics
Analysis of three datasets for count data analysis, survival analytics and missing value imputation .

This report consists of three topics mainly,

1.Count Data Regression- To think beyond linear regression ? Linear Regression not giving desired results? If you are stuck at this stage  Linear Regression might not be te apt choice in the case of handling count data.Possion Regression and Negative Binomial could be explored.
     
     Briefing about dataset -Beluga Whale Calves at the Aquarium for Wildlife Conservation
     In August 1991, two beluga whale calves were born at the Aquarium for wildlife
     conservation at Coney Island, New York. These two calves (Hudson & Casey) were
     the first in the world to be successfully born and raised to maturity in captivity. They
     were also the first cetaceans born in captivity for which detailed quantitative
     information about the births and early lives of the animals was gathered. The
     file whale.csv contains information about the nursing behavior of the calves during the
    first 55 days of their lives. The observations refer to 6-hour time periods and give the
    time period, the number of nursing bouts for that time period (a successful nursing
    episode where milk was obtained from the mother), the number of lockons for that
    period (when the calf attached itself to the mother while suckling milk from a
    mammary gland), and whether the time period was during the day (coded 1) or night
    (coded 0). It is well known that nursing patterns can be highly informative regarding
    the health of an infant, so it is important to try to understand nursing behavior as well
    as possible.
    The variable of interest is the number of lockons. We treat the records on two calves,
    Hudson and Casey as two different data sets.


2.Survival Analytics - Survival analysis is a branch of statistics for analyzing the expected duration of time until one or more events happen, such as death in biological organisms and failure in mechanical systems. Survival analysis attempts to answer questions such as: what is the proportion of a population which will survive past a certain time? Of those that survive, at what rate will they die or fail? Can multiple causes of death or failure be taken into account? How do particular circumstances or characteristics increase or decrease the probability of survival? One such dataset with one such question is analyzed in this part.
    
    Briefing about dataset -The data set called leukemia.csv consists of remission survival times on 42 leukemia
    patients, half of whom get a certain new treatment therapy and the other half of whom
    get a standard treatment therapy. The exposure variable of interest is treatment status
    (Rx=0 if new treatment, Rx=1 if standard treatment). Two other variables for control
    as potential confounders are log white blood cell count (i.e. logWBC) and Sex. Failure
    status is defined by the relapse variable (0 if censored, 1 if failure).


3.Missing Data Imputation using MICE - this part of the report helps to compare and correct the problems caused by missing data with modelling.First we try to fit a linear model in a dataset with some missing values and then we impute the data and apply model into it.The results are astonishing.

    Briefing about dataset -Biometric information was collected on all the students of a class for class analysis.
    Data on age (in years), height (in inches), and weight (in pounds) of the students are
    given in class_data.csv. The gender of each student is also noted and coded as 1 for
    women and 0 for men. The aim is to study the relationship of weight on other
    variables. Hence weight is the response variable and the rest of the variables are
    predictors.
