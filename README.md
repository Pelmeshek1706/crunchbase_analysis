# Analyze companies from UK   
#### made by [@pelmeshek1706](https://telegram.me/pelmeshek1706)

In this task I needed to build a simple model to explain the total funding raised by one or more variables. 

The data taken from crunchbase has information about companies from the UK. 
 
 All used libraries:
- <code>numpy</code>
- <code>pandas</code>
- <code>matplotlib</code>
- <code>sklearn</code>
- <code>time</code>


### Analyzing the model results

![crunchbase_model](https://github.com/Pelmeshek1706/crunchbase_analysis/assets/94761102/86f5f4a8-f6ac-41fd-a739-aefe2241f5d4)


Excluding Last Funding Amount, the indicative criteria for funding are Tags - Exited Unicorn. That is, new investors will want to invest more money in a Unicorn than in a regular company. 

Also, the fact that the company already has a range of estimated revenues from 1 to 10 billion also gives hope for new investments. 

#### Model evaluation
Best parametrs: {'max_depth': None, 'min_samples_leaf': 1, 'min_samples_split': 2, 'n_estimators': 50}
R-squared (R2): 0.8042928439775665



