# miRNA_MVCT
Multi-view co-training applied to microRNA prediction. Accompanies "Multi-view Co-training for microRNA Prediction" manuscript by Mohsen Sheikh Hassani &amp; James R. Green
The "pipeline.py" file demonstrates the general framework of the multi-view co-training process. During each learning iteration, the top two positive and negative instances predicted by one view are added to the initial training set of the other view. 
"Featureset.py", written by Rob Peace, extracts the sequence and expression-based features. 
"Smote.py" is used for class imbalance correction.
