Overview of the analysis: 

    With knowledge of machine learning and neural networks, use the features in the provided dataset 
    which  is a CSV file containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.
    Help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
    
Results: 
  Address the following questions.		

  Data Preprocessing	
  
		What variable(s) are considered the target(s) for your model?

      IS_SUCCESSFUL
      
		What variable(s) are considered to be the features for your model?
    
      INCOME_AMT
      
      AFFILIATION
      
      USE_CASE
      
      AK_AMT
      
      CLASSIFICATION
      
      
      
		What variable(s) are neither targets nor features, and should be removed from the input data?
    
          NAME, EIN
      
          These variables do not affect or influence the outcome.
    
    
	Compiling, Training, and Evaluating the Model	
  
		How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
      Tried different attempts 
    
        1st - 2 hidden layers
        2nd - 3 hidden layers
        3rd - 5 hidden layers
    
      Reason to select more hidden layers was to get the model 
    
		Were you able to achieve the target model performance?
        The best accuracy my model could achieve was 73.1%.
        This was the best onmy part. Need to invest more time to get a better accuracy.
    
		What steps did you take to try and increase model performance?
        An attempt was made to remove encoding to investigate if reduced number of columns will improve model behaviour.
        The encoding was removed and original charactheristics of data was mainained.
        Though this did help improve the accuracy, it could not be determidned fool proof that I am headed in the right direction.
        
3. Summary: 
      Summarize the overall results of the deep learning model. 
      
      Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.	
      
