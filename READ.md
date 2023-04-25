# Speaker-Independent Spoken Digit Recognition (xSDR)

One of the successful stories of deep neural networks is the proliferation of commercial of automatic speech recognition (ASR) systems. This project aims to explore one application of ML-powered ASR to the problem of spoken digit recognition (SDR). Since digits are widely used as unique identifiers for bank information, social security numbers, post codes, etc, SDR systems can be an efficient alternative to fully-fledged ASR systems since the domain is more predictable than other applications of ASR. 

In this project, we focus on developing a SDR system in a speaker-independent setting. That is, the speakers in the evaluation set are disjoint from the training set speakers. We do so because we expect real-world ASR systems to generalize to different speakers than those we have data for. Moreover, for many languages that are under-resourced, we have have (limited) annotated speech data from a single speaker, but we would still want the system to be deployed to work on any speaker of that language. We tackle the problem of spoken digit recognition as a sequence classification task. Concretely, the inputs are short audio clips of a specific digit (in the range 0-9), then the goal is to build deep neural network models to classify a short audio clip and predict the digit that was spoken.

# Authors -
		Suraj Sudhakar 7015702
		Ganavi Basavaraju 7015432
		Keerthana Krishnamurthy Burly 7023672

Python 3.9.7

Please install the libraries found in requirements.txt

The project folder contains
1. Project_Notebook.ipynb -- notebook with the project tasks implemented.
3. Project_Report.pdf   -- report in pdf format
4. contrastive							  -- folder contains contrastive learning code, imported to the notebook
5. requirements.txt						  -- libraries
6. speech_data							  -- speech data folder
7. SDR_metadata.tsv						  -- metadata file

