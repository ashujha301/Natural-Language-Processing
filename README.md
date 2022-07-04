# Natural-Language-Processing
Named Entity Recognition using NLP

Source of Data Collection: Individual Data series collected from (World Bank Project:- Projects & Operations | The World Bank) 
Data Dimensions:

•	Attributes- 21000

•	26 features

*Feature selection*

Now for the feature selection I have used the autogluon library which gives the data types and its features so that we can choose accordingly for our prediction model.

AutoGluon correctly recognized our prediction problem to be a binary classification 

*Entity extraction*

For the the extraction of the keyword from the data we have to use the NAMED ENTITY RECOGNITION (NER)

*Created NER csv file with new columns*

there are multiple columns in the source file that contain text where we want to find entities

--> we can add all the required columns for the further evaluation of NER

-->NER csv columns are used for the keyword extraction from the dataframe

-->It joins the NER or evaluated columns to the last which has the keywords or text



