# Two-level-classification
### Files

  "train_2ndlayer.csv" :output of first layer models on train set. 
  
  "labels_2ndlayer.csv" :labels for 'train_2ndlayer.csv', the same as initial labels
  
  "test_1stlayer_avgEnsemble_output.csv" :output of first layer models on test set, predictions of each model are averaged between 5 fold                                            models

### Output files structure
[Densenet121_BCE(14 classes), Densenet121_FocalLoss(14 classes), InceptionV3_BCE (14 classes), InceptionV3_FocalLoss(14 classes)]



RFC #1 params:  n_estimators=15, max_depth = 10, min_samples_leaf=510, max_features = 50
