Steps involved </br>
1> write a function to download the data from the web </br>
2> Parse emails and create list of ham and spam emails </br>
3> Analyze the structure of emails  </br>
4> Seperate training and test data . Create labels 0 for ham emails and 1 for spam emails </br>
5> write a function to return plain text from email of any format </br>
6> Make two transformers </br>
  a> Converts ecah email to counter of its words with hyperparameters like strip headers,lower_case etc </br>
  b> second transformer s fit method will build a vocabulary and transform method will use the vocab to convert word counts to vectors  </br>
7> Build a preprocessing pipeline from the two transformers  </br> 
8> Used the Logistic Regression model as classifier and calculated the cross_val_score accuracy  </br>
9> Predicted the email classification of test data and computed precision and recall  </br>
     
