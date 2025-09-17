# Speech Emotion Recognition (SER)

## Group Members
- Jonathan Newman (100909996)  
- Gillian Wood (100912624)  
- Riley Singfield (100926159)  

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

## Datasets (In folder datasets)
We will use two publicly available emotional speech datasets:  

### 1. RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)  
- Contains vocal and audio-visual data  
- Includes neutral speech, songs, and acted emotions  
- Each emotion read twice with different intensities per actor  
- Recorded by undergraduate students in Toronto (less variety in age and accent)  
- Highly rated for quality and consistency  

### 2. CREMA-D (Crowd-sourced Emotional Multimodal Actors Dataset)  
- Includes diverse actors across different ages (20–74) and ethnicities  
- Provides more accents and cultural diversity than RAVDESS  
- 12 sentences per actor  
- Multiple intensity levels (low, medium, high)  

Together, these datasets provide both **quality-controlled** and **diverse** emotional speech data.

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

## Plan
- Find source code and datasets  
- Start with simple classification methods  
- Explore existing algorithms  
- Test robustness against noise and blended data  
- Compare performance of different approaches 
