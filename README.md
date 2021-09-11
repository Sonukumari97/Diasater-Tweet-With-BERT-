# NLP with Diasater-Tweet
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. 
Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).
But, it’s not always clear whether a person’s words are actually announcing a disaster.

to classify disaster tweet we use libraries as follows :
 - skleran
 - matplotlib
 - tensorflow : to get TfBertModel 
 - text_hammer : to do text pre-processing 
 - RandomForest 
 - nltk : natural language tranfer toolkit 
 - WorldCloud : visualization technique for texts 

Here we use different approch to classify tweets 
1. RandomForest
   - Accurcay : 78.60%
2. BERT MODEL 
   - Accuracy : 83.38%
