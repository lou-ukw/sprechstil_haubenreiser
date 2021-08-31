
# Maschinelle Eigenschaftsanalyse

This is a project dedicated to the classification of emotional speech and was created in class with Prof. Dr. Burkhardt at Technische Universität Berlin.
After holding a short speech in class, the aim of the project was to analyze the voice recording by taking a closer look at target acoustic features such as the HNR, the mean F0Hz or jitter. 

The project uses Jupyter, an open-source web application that allows you to create and share documents that contain live code that can be used for statistical modeling and data visualization.


## Learning Objectives

- Introduction to Python and Juypter Notebook
- Classification of Emotional Speech
- Acoustic Analysis through Extraction and Analysis of Expert and Brute-Force Features
- Visualization of Statistical Findings


## Preparation

In order to run this project, some preliminary steps are necessary:
- Create a virtual environment for the project and collect the necessary imports. If a certain plug-in is missing, it is recommended to install it via Pip in the terminal, so that the import into Jupyter Notebook can run smoothly. You will definitively need: Pandas, os, Matplotlib, seaborn, glob, NumPy, Parselmouth and SciPy.
- Prepare the audio file for the analysis. The format should be: wav, 16kHz, 16bit, PCM (possible tool: SoX/Audacity).
- Segment and annotate your data according to the dimension  (or a dimension/category of your choice) on a 10-level Likert scale (possible tool: Audacity, Speechalyzer).


## Documentation

After configuring a python environment with Jupyter notebook the audio and its annotations are first imported into a pandas table and then analyzed step by step according to the Feinberg PraatScripts. 
Necessary information on the single steps is included in the notebook.

#### Extracting Acoustic Features

The [PraatScripts](https://github.com/drfeinberg/PraatScripts) offer a comprehensible code to perform your analyses. Nevertheless, you might need to adapt the scripts to fit your needs.

The overall analysis includes:
- Formants
- HNR
- Pitch
- Intensity
- Jitter
- Shimmer
- Speech Rate
- Pauses
- Vocal-tract Length Estimates

#### Visualization
The project includes different approaches to visualize the data using the tools seaborn and Matplotlib for e.g. scatter plots, box/violin plots or cluster plots.

  
## Credits

 - [Speechalyzer](https://github.com/felixbur/Speechalyzer)
 - [Feinberg PraatScripts](https://github.com/drfeinberg/PraatScripts)
 

  
#### Author: [@lou-ukw](https://www.github.com/lou-ukw)
