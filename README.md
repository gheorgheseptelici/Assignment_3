# Prompting Strategies for the Ollama 3.2 LLM Prediction Model

## Project Description:
This project aims to use Ollama 3.2 LLM to predict genres for song lyrics using two prompting strategies: zero-shot and few-shot. The results of the generated outputs are then evaluated against the labels that were already given in the dataset, using Precison, Recall and F1 score. The predictions were applied to 5 instances of lyrics from the entire dataset, due to limited time for the assignment and intensive computational demands from the used model. Furthermore, in the few-shot strategy part, 10 instances of lyrics and their respective genre, which were pre-assigned in the original dataset, were used as training examples for the generation of new predictions. These two methods allow to compare how various strategies of prompting yield different results and how the few-shot strategy can enhance the possibility of more accurate predictions. 

## Data
All the data from the 'genreLyrics.csv' file was converted into a Pandas DataFrame object and slightly formatted for any remaining unecessary characters. The columns from the DataFrame that were used have the following descriptions:
| Header        |Description            |
| ------------- |:-------------:|
| genre | The genre label as annotated before the prediction model  |  
| lyrics | The lyrics content on which the predictions were operated    |    
| pg_zero_shot | The genre label predicted by the model using the 'Zero-Shot' strategy       |
| pg_few_shots | The genre label predicted by the model using the 'Few-Shot' strategy        |

A discussion of the results has been submitted in a separate report on Brightspace.


