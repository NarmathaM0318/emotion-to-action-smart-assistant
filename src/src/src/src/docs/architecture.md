# System Architecture

The Emotion to Action Smart Assistant consists of three major input modules:

1. Facial Emotion Recognition
   - CNN / ResNet-50 based analysis
   - Face detection and emotion classification

2. Voice Emotion Recognition
   - MFCC feature extraction
   - BiLSTM based emotion prediction

3. Text Emotion Classification
   - BERT transformer model
   - NLP-based emotion understanding

The outputs from these modules are combined using an attention-based multimodal fusion mechanism to generate emotion-aware actions.
