# CMPT 353 project: COVID-19 Cough Classification

## Installing Required Libraries 

- Linux

`sudo apt-get install python3 python3-dev python3-pip`<p>
`sudo apt-get build-dep python3-scipy python3-matplotlib`<p>
`pip3 install --user scipy matplotlib pandas statsmodels scikit-learn jupyter librosa soundfile geopandas`

- Anaconda

`conda install librosa soundfile`

## Index

### Audio_data_model.ipynb
- notebook to process and extract data from audio files of patients coughing
- extract numerical feature data from audio signals
- train KNN model of features such as MFCC, Spectral bandwitdh, Zero Crossing Rate
- plots include audio wave visualization
usage of librosa and soundfile along with sci-learn Libraries

### image directory
- includes all plot and data visualization created

### model_note.ipynb
- notebook to build and train models to predict whether the features in our data can predict whether or not someone has COVID-19
- models include Linear Regression, Neural Network, Decision Tree, Random Forest, Naive Bayes, SVM (Feature Scaling), KNN (Feature Scaling), Voting Ensemble (includes: RF, GB, KNN, SVM).

### pieplot.ipynb
- notebook creates pie plots visualizations from audio data
- filters NAN values from metadata

### plot_note.ipynb
- notebook to extract and visualize the metadata csv file
- plots are for all of the boolean and categorical columns
- excludes numerical columns such as 'SNR' and 'cough_detected'
- plots include bar graphs and pie charts

### Report353.pdf
- report on project work with data analysis and visualization
- include project experience summary

### worldplot.ipynb
- extracts latitude and longitude values from metadata
- outputs the data points as a scatterplot on the world map
- usage of matplotlib , plotly.express and other python modules

## References 
Dataset: `https://www.kaggle.com/andrewmvd/covid19-cough-audio-classification`
`https://www.kdnuggets.com/2020/02/audio-data-analysis-deep-learning-python-part-1.html`

