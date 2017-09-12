# Music-Genre-Identification
Machine Learning to identify music genres

This project utilizes data from the [Free Music Archive](https://github.com/mdeff/fma) to predict genres given an audio waveform in an MP3 file.

### Requirements:
- Python
  - [librosa](https://github.com/librosa/librosa)
  - scikit-learn
  - pandas
  - jupyter notebook
- [FFMPEG](https://www.ffmpeg.org/)

### Files:
`Work.ipynb`: All the cleaning, signal processing and modeling is done in this notebook.  
`Model.ipynb`: Consolidated the signal processing and the pickled model if you're interested in playing with the model.  
`model.pkl`: Pickled model: index 0 is the trained model, index 1 is the label decoder (see sklearn and pickle documentation for details)
