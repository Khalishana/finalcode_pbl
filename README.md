# finalcode_pbl
This is the source code for the final assignment of Speech Processing course, focusing on preventing catastrophic forgetting in transfer learning-based Text-to-Speech (TTS) 
systems for multilingual synthesis in Javanese and English. This project builds a TTS system using FastPitch architecture and interleaved replay, 
a continual learning strategy that enables the model to retain prior knowledge (English) while learning a new low-resource language (Javanese). 
<br>
In this project, two models were trained:
- **Model 1 (M1)**: Fine-tuned only on Javanese dataset
- **Model 2 (M2)**: Trained with Interleaved Replay using Javanese and LJSpeech datasets

FastPitch repository for data preprocessing setup: https://github.com/NVIDIA/DeepLearningExamples/tree/master/PyTorch/SpeechSynthesis/FastPitch

### Datasets
- [Javanese Dataset (OpenSLR)](https://openslr.org/41/)
- [English Dataset (LJSpeech)](https://keithito.com/LJ-Speech-Dataset/)
