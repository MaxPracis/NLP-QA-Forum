# NLP on QA Forum
This is the project dedicated to Professor Ta ! \
We predicted the best answers of the questions using the features provided, including the texts. \
*Since the data is too large (283MB) to upload on the git, there is only the codes. 
## Data Preparation
- Time data treatment
- Label encoding
- Embedding using Word2Vec
- Down / Upsampling for the umbalanced target variable

## Modelling
- Xgboost: ROC-AUC 84%
- Neural Network (linear stack of layers): Accuracy 92%, MSE 0.08
