# Speech Emotion Recognition (SER)

## Project Idea
There is no definitive way to determine emotions from speech. The Speech Emotion Recognition (SER) system is defined as a combination of different frameworks that analyze audio signals to identify emotions.  

The human brain separates emotions from speech by dividing it into three parts: **acoustic, lexical, and vocal**.  
For this project, we will focus on the **acoustic part of speech** (pitch, jitter, tone, etc.).

## Industry
- Communication  
- Entertainment  

## Problem Type
- Categorization  
- Classification  

**Example:**  
A system differentiating between elephants and dogs may look at features such as images, weight, or height.  
In the same way, our system will learn which features of speech help classify emotions.

## Methodology
- Classical machine learning (e.g., k-means, hierarchical clustering)  
- Deep learning-based classification  
- Comparative analysis of different methods  
- Testing sensitivity to variations (e.g., noise, overlapping voices, background sounds)  
- Preprocessing techniques (e.g., ICA for source separation)  
- Tracking emotions over time (e.g., analyzing speech in a movie scene to graph emotional shifts)  

## Dataset
We will use the **Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)**:  
- 7,356 audio files  
- 24 professional actors (12 female, 12 male)  
- Two lexically-matched statements spoken in a neutral North American accent  

## Libraries
- Keras  
- TensorFlow  
- librosa  
- soundfile  
- scikit-learn  
- pandas  
- matplotlib  
- NumPy  
- pickle  
- mlfoundry  

## Group Members
- Jonathan Newman (100909996)  
- Gillian Wood (100912624)  
- Riley Singfield (100926159)  

## Why It’s Interesting
**Jonathan:** Interested in seeing if a computer can recognize emotions in speech better than himself.  
**Gillian:** Fascinated by how a computer can analyze tone and intention in ways humans may overlook.  
**Riley:** Excited to
