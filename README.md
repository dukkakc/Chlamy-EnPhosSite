# Chlamy-EnPhosSite

Chlamy-EnPhosSite: A deep learning-based approach for Chlamydomonas reinhardtii-specific phosphorylation site prediction.
# Requirement
  Backend = Tensorflow <br/>
  Keras <br/>
  Numpy <br/>
  Biopython <br/>
  Sklearn <br/>
  Imblearn <br/>
 # Dataset
 Dataset is in FASTA format which includes protein window size of 57. Test dataset is provided. There are two dataset for positive and negative examples.
 # Model
 There are two models included. Multi-window based model(Chlamy-MwPhosSite) and ensemble stacking based model (Chlamy-EnPhosSite).The pretrained model file with format *.h5 is included.  
 # Prediction for given test dataset
 With all the prerequisite installed, run -> model_multi.py to run Chlamy-MwPhosSite or run -> model_stacking.py to run Chlamy-EnPhosSite respectively.
 # Prediction for your dataset
 The format should be same as the test dataset which is basically FASTA format. Input fasta file should have window size of 57 and added to test dataset portion in the model code. 
 # Contact 
 Feel free to contact us if you need any help : dukka.kc@wichita.edu
