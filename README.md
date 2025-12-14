# transformer_for_emotion_prediction_on_gsr_ecg
A transformer model that predict emotions using GSR and ECG biosignals. The model is trained using the BIRAFFE2 dataset

## Output
Due to the limitation of the dataset, the output of the model is two components called Negative and Positive Affect18
which are calculated using the Game Experience Questionnaire (GEQ). The postfix number 18 after the Affect refer to
the paper in which the way to calculate those component.

## Future
The code is still a mess due to my crowded schedule, however, it will be improved overtime and more explainations
and visualizations will be added here.

## Performance
For a quick overview of the model performance so far see the table.
Model Performance Matrices Of Negative Affect18

|              | Precision | Recall | f1-score | Support |
|:------------:|:---------:|:------:|:--------:|---------|
|       0      |   0.471   |  0.718 |   0.569  |   294   |
|       1      |   0.608   |  0.315 |   0.415  |   197   |
|       2      |   0.437   |  0.326 |   0.373  |   233   |
|              |           |        |          |         |
|   Accuracy   |           |        |   0.482  |   724   |
|   Macro Avg  |   0.505   |  0.453 |   0.452  |   724   |
| Weighted Avg |   0.497   |  0.482 |   0.464  |   724   |