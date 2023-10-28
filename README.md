# Text-to-Speech-using-Tacotron2
Converting text to audio and applying audio augmentation


## Topic
In this notebook I will experiment with speech synthesis from text using Tacotron2 which is a deep neural network that uses sequence to sequence architecture and which produces a 
mel spectromgram out of a text and then converts it to audio using Vocoder. After extracting the audio I will then use a series of audio augmentation techniques to make the sound more
natural. So let's get started !

## Objectives
- Convert text to audio
- Use audio augmentation to enhance the extracted audio


## Summary
- Importing libraries
- Text to speech
- Adding white noise
- Time stretching
- Pitch scaling
- Inverting polarity
- Random gain
- Conclusion

## Libraries
- Torchaudio
- Numpy
- Ipython
- Librosa
- Matplotlib
