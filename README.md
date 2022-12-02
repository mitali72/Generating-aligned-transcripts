# Generating-aligned-transcripts

This repo contains colab notebooks for evaluating Vakyansh stages on News On AIR broadcast audio and performing speech-text alignment.

Dataset: https://newsonair.gov.in/RNU-NSD-Audio-Archive-Search.aspx

Vakyansh.ipynb contains:
1. VAD using WebRTC
2. WADA-SNR
3. Speaker clustering

Silero.ipynb contains:
1. VAD using silero (version 3.1)
2. WADA-SNR
3. Speech-to-text using whisper https://github.com/openai/whisper

TextAlignment.ipynb contains:
1. Edit distance based approximate string matching
2. String similairty based approximate string matching using SequenceMatcher

Presentation slides: https://docs.google.com/presentation/d/1QASQzU3CN_96FYXlWrz7_TDRCD5oKua1dXQenlPHxKI/edit#slide=id.g35f391192_00 
