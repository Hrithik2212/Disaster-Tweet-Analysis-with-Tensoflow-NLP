# Disaster-Tweet-Analysis
![python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit%20learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![numpy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=NumPy&logoColor=white)
![tensorflow](https://img.shields.io/badge/-Tensorflow-FF6F00?style=flat-square&logo=Tensorflow&logoColor=white)
![pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=Pandas&logoColor=white)
![jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white)

### This Project aims to classify Tweets wether they are related to a Disaster or Not using Deep Learning 

* The following Models are built in the Jupyter Notebook and their metrics are given 

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Model</th>
      <th>Accuracy</th>
      <th>Precission</th>
      <th>F1 Score</th>
      <th>Recall</th>
      <th>ROC_AUC</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Naive Bayes</td>
      <td>0.803150</td>
      <td>0.872180</td>
      <td>0.755700</td>
      <td>0.666667</td>
      <td>0.792271</td>
    </tr>
    <tr>
      <th>1</th>
      <td>ANN - TwoLayers</td>
      <td>0.763780</td>
      <td>0.900000</td>
      <td>0.677419</td>
      <td>0.543103</td>
      <td>0.746189</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Simple RNN</td>
      <td>0.730971</td>
      <td>0.763838</td>
      <td>0.668821</td>
      <td>0.594828</td>
      <td>0.720119</td>
    </tr>
    <tr>
      <th>3</th>
      <td>LSTM</td>
      <td>0.761155</td>
      <td>0.798561</td>
      <td>0.709265</td>
      <td>0.637931</td>
      <td>0.751333</td>
    </tr>
    <tr>
      <th>4</th>
      <td>GRU</td>
      <td>0.753281</td>
      <td>0.779720</td>
      <td>0.703470</td>
      <td>0.640805</td>
      <td>0.744315</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Bidirectional LSTM</td>
      <td>0.766404</td>
      <td>0.785235</td>
      <td>0.724458</td>
      <td>0.672414</td>
      <td>0.758912</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1D Covalutional Layer</td>
      <td>0.758530</td>
      <td>0.780822</td>
      <td>0.712500</td>
      <td>0.655172</td>
      <td>0.750292</td>
    </tr>
    <tr>
      <th>7</th>
      <td>TF Pretrained Hub</td>
      <td>0.796588</td>
      <td>0.800623</td>
      <td>0.768311</td>
      <td>0.738506</td>
      <td>0.791958</td>
    </tr>
    <tr>
      <th>8</th>
      <td>TF Pretrained hub with 10% data</td>
      <td>0.776903</td>
      <td>0.824818</td>
      <td>0.726688</td>
      <td>0.649425</td>
      <td>0.766742</td>
    </tr>
  </tbody>
</table>
