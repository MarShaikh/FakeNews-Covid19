# FakeNews-Covid19
Fake News detection for Covid-19 data. Jupyter notebooks found here contain of the following:
<ul>
  <li>LSTM Model without spatio temporal features</li>
  <li>LSTM Model with hyper parameterization</li>
  <li>Model with country and date information</li>
</ul>

# Getting started
Install the dependencies from the <em> requirements.txt </em> file <br>
  <code>pip install -r requirements.txt </code> </br>
  
  After installing the required dependencies, the project files are <em>LSTM_RNN_Implementation_with_hyperparameterisation.ipynb</em> and <em>Country_Date.ipynb</em>, where models with and without spatial and temporal features are present respectively. These two notebooks were run on Google Colab to use their GPU for faster training performance; The required dataset is present under the <em>Datasets</em> folder, which in our case had to be uploaded to drive, and the folder mounted on drive. <br>
  
  Hyperparameter Optimization was done with the help of a package, <code>talos</code>. The best hyperparametersparameters required were then visualized in the the files <em>Hyperparameter_Optimization1.ipynb</em> <em>Hyperparameter_Optimization2.ipynb</em> 
  
 # References 
 
 Autonomio Talos [Computer software]. (2019). Retrieved from http://github.com/ autonomio/talos
