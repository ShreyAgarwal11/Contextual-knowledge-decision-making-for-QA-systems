# NLP_Project

# The primary obstacle in developing Question Answering (QA) models revolves around untangling the impact of parametric knowledge (knowledge inherent in model weights) and contextual knowledge (external information) on generating answers during the inference process. To overcome this challenge, our project introduces a solution known as "post-hoc knowledge injection." This strategy seeks to mitigate the complexity of choosing among multiple external knowledge sources, ultimately enhancing the informativeness of the generated answers.

# A subset of the NQ dataset (above 35GB, hence cannot be added here) is used for the purpose of this project. Link to dataset: https://ai.google.com/research/NaturalQuestions/download
# Firstly, the preprocessing is done to the above mentioned data as part of the NQDataset_pre_processing.ipynb notebook.
# The outputs of this preprocessing is stored in the NQ_Dataset folder of this repository.
# These outputs are then passed to the Dataset_Creation.ipynb notebook which concatenates and writes the train and test dataset into the Data folder of this repository.
# The parametric model is trained as part of the Parametric_model.ipynb notebook and its test output is stored in the Data/parametric_answers.csv file present in the Data folder of this repository.
# Consequently the contextual answer generation and final analysis related code is present in the Contextual_Answer_Generation.ipynb notebook.
