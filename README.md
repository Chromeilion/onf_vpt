# Pay Attention to the Keys: Visual Piano Transcription Using Transformers - Supplementary Materials

Visual piano transcription (VPT) focuses on extracting a symbolic representation of a piano performance from visual information only (e.g., from a top-down video of the piano keyboard).
In this work, we propose a Vision Transformer (ViT) based system for VPT which surpasses previous visual methods based on convolutional neural networks (CNNs).
Our system is trained on a new dataset, R3, which contains 31 hours of synchronized video, MIDI, and audio recordings of piano performances.
For this task we additionally introduce an approach to predict note offsets, which has not been previously explored in this context, and we apply it to our method as well as to the CNN based methods.
We show that our system outperforms the state-of-the-art on the PianoYT dataset and that training on our dataset, combined with the proposed offset prediction method, 
improves the performance of both our ViT based system and the CNN based methods.

Here we provide a a supplamentary Appendix, as well as Google Colab showcasing the inference procedure of our model and a YouTube playlist with example predictions:

{% include youtube.html id="h0KDyuaJoFM" %}

Appendix: https://drive.google.com/file/d/1j4DF0vS0IS9DvKmDFiUCPawk0s6oxnWP/view?usp=sharing

Google Colab: https://colab.research.google.com/drive/1ELUdXTQi9cxSBjqaw0y8dZ-Dbquqxj74?usp=sharing

YouTube playlist: https://youtube.com/playlist?list=PLyLgj1bgnXAc1SmWUDLV_OcTP6IGxkjZF&si=D-hGNBon7Vqjx3Fc

Code: https://github.com/Chromeilion/ppan
