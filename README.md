In this repository are all the data used and the code made to carry out the study.
- Data: 
  - Sensorama_JSON.json: database that relates the characteristics of the components to their olfactory relationships through their cid (Compound ID number) made by Aitor Gonzalez.
  - sensorama_df.csv: Data frame made from Sensorama_JSON.json data.
- Scripts: 
  - sensorama_df.ipynb: jupyter notebook with all data transformation processes.
  - SVM.ipynb: jupyter notebook with support vector machine algorithm, for different kernels, classifying odor levels. 
  - RF.ipynb: jupyter notebook with two Random forest Classifiers. The first one, classifying all data in odor levels; the second one, using feature Importances for each odor level.
  - RF_FI.ipynb: jupyter notebook with Random forest Classifier using a reduced dataset with all features importances that are not common.
  - DT.ipynb: jupyter notebook with odor level classifier algorithm using decision trees.
  - LR.ipynb: jupyter notebook with Logistic Regression algorithm for classifying odor levels.
  - KNN.ipynb: jupyter notebook with KNN algorithm searching the best k for every odor level classifier.
  - L1_OdorName.ipynb: jupyter notebook with all the algorithms said before but using a reduced dataset containing only molecules from odor level 1. The aim is to classify the odor name.
  - L2_OdorName.ipynb: jupyter notebook with all the algorithms said before but using a reduced dataset containing only molecules from odor level 2. The aim is to classify the odor name.
  - L3_OdorName.ipynb: jupyter notebook with all the algorithms said before but using a reduced dataset containing only molecules from odor level 3. The aim is to classify the odor name.
  - L4_OdorName.ipynb: jupyter notebook with all the algorithms said before but using a reduced dataset containing only molecules from odor level 4. The aim is to classify the odor name.
  - L5_OdorName.ipynb: jupyter notebook with all the algorithms said before but using a reduced dataset containing only molecules from odor level 5. The aim is to classify the odor name.
  - L6_OdorName.ipynb: jupyter notebook with all the algorithms said before but using a reduced dataset containing only molecules from odor level 6. The aim is to classify the odor name.
  - L7_OdorName.ipynb: jupyter notebook with all the algorithms said before but using a reduced dataset containing only molecules from odor level 7. The aim is to classify the odor name.
  - L8_OdorName.ipynb: jupyter notebook with all the algorithms said before but using a reduced dataset containing only molecules from odor level 8. The aim is to classify the odor name.
