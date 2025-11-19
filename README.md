# Performance Complexity in NCT 127
Quantifying and Modeling Musical Hardness Using Audio Features and Spectrogram-Based Learning

## Overview
This project analyzes the musical complexity and performance difficulty of seven NCT 127 title tracks using:
- Spotify API and Librosa for feature extraction
- A handcrafted Difficulty Index
- PCA and clustering for visualization
- A CNN model for spectrogram-based classification

The goal is to provide scientific evidence supporting the group’s reputation for vocally and structurally challenging music.

## Methods
- **Feature Extraction**: Tempo, MFCC variance, pitch range, onset strength, etc.
- **Scoring**: Complexity and hardness indexed 0–1
- **Modeling**: CNN classifier using Mel-spectrograms (3-class: easy, medium, hard)
- **Evaluation**: PCA plots, training curves, confusion matrix

## Tools Used
- Python (Colab)
- Librosa
- Spotipy
- Matplotlib / Seaborn
- Scikit-learn
- TensorFlow/Keras

## File Structure
- `complexity_model.ipynb`: Main notebook (cleaned and annotated)
- `data/`: Sample feature files
- `images/`: Spectrograms, PCA plots, model outputs
- `models/`: (Optional) Trained CNN model

## Example Outputs
- Sticker: High complexity + medium hardness
- Kick It: High hardness (percussive + pitch range)
- Ay-Yo: Lower overall difficulty

📄 **Read the Full Paper (PDF):**  
[Performance Complexity in NCT 127 – Full Paper](Performance%20Complexity%20in%20NCT%20127%20Quantifying%20and%20Modeling%20Musical%20Hardness%20Using%20Audio%20Features%20and%20Spectrogram%20Based%20Learning%20draft.pdf)

## Author
Imas Viestawati
Independent Researcher  
If you find this useful, feel free to like the repo!


