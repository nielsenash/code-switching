### Overview and Motivation

This is a project designed to explore how well large language models are able to predict changes in language. This project focuses primarily on English-Spanish code switching since I am very familiar with both languages. I have also used spanglish frequently and have interacted with people who use spanglish regularly, so this topic is interesting to me. I have also learned that current language models have advanced translation and transcription abilities for single languages, however that ability is significantly reduced when languages are mixed. There's still a lot of work to be done in this area, so I'm excited to explore!


### Process

- installed libraries and packages necessary for processing dataset and making predictions including whisper, librosa, and torch
- ran whisper prediction on an australian dataset (Pure English)
- ran predictions on an English-Spanish code-switching dataset
- listened to a sample of predictions 
- calculated WER for 50 samples 

### Insights

- Whisper can sometimes predict a totally different language than the actual input language