# READ ME FILE

Addressing Questions from Supervisor

Comment: Please explain further why DT, RF and LR have been selected. For example, why not SVM for the first question?

  o Moving forward projet to also evaluate SVM for the following reasons. SVM are better at handling complex non-linear patterns, outliers, and dealing with imbalanced data. Also because had to fill in missing user and critic scores, and remove null values our data may be slightly imbalanced and therefore better suits SVM.

Comment: Also, review filter-based, wrapper, and embedded/hybrid techniques to obtain the influential predictors, apply one of each, and then compare the resulting ranked lists. Notably, some feature selection techniques may work better for specific types of predictive models, such as linear regression versus decision trees. For example, regularization techniques such as Lasso or Ridge regression may work well for linear models with many features. However, they may be ineffective for decision tree models that can handle non-linear relationships and interactions. 

  o Project to explore the above feature selection techniques. Need support with this type of technique

Comment:	Which evaluation technique do you plan to use - k-fold, time-series, or Leave-one-out CV? Each technique has pros and cons, and the choice should depend on the specs of the dataset.
   
   o Project to explore the above evaluation techniques. Planning to use K fold as the data set is medium size and too big for leave one out cross-validation. Also the data is not time-series focused.

Comment:	Apart from evaluating the performance, the predictive models' efficiency needs to be evaluated using metrics like training time or memory consumption. Furthermore, examining the Stability of the models would be best.
    
  o	planning to use memory_profiler and psutil libraries to evaluate the models

Comment:	For the NLP question, please detail the pre-processing steps you plan to take to cleanse and denoise the textual data: removing punctuation, converting text to lowercase, removing stop words, and stemming or lemmatization. Also, when planning to use the Word2Vec model, specify the size of the word chunks. For example, Will you consider each word individually (uni-gram) or pairs of adjacent words (bi-gram). I would also apply a topic modelling approach like LDA to investigate respective topics.
  
  o there will not be any NLP needed to answer any of the research questions outlined

Comment: Please check the context and the reasons for the 5019 duplicated rows. If they result from errors or data quality issues, remove them. However, removing them might lead to a loss of valuable information if they reflect legitimate instances of repeated observations or events.
  
  o Duplicate names are not an issue because many games are released on multiple platforms  	

Comment: Please note that imputation methods and those treating imbalanced classes are to be applied to training sets to avoid data leakage to test sets.
  
  o	  No imputation used 


Comment: The HeatMap that shows the bi-variate analysis lacks the name of the statistical test. Ensure you selected the appropriate statistical test to investigate the multicollinearity between the independent variables. For instance, using Spearman instead of Pearson may be more appropriate when dealing with discrete variables.
  
  o Updated Bi-variate analysis to include statistical coefficient
  o Outlined both Spearman and Pearson


Comment:	I would also like to see a comprehensive exploratory analysis, including univariate and bivariate analyses, and once completed, please upload the report to your GitHub account and share the link.
  
  o Visualized Critic Scores via box plot	
  o Visualized Genres of game and their sales in Japan and North America

