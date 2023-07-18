# AI-Song-Cover-RVC
All in One Version : Youtube WAV Download, Separating Vocal, Splitting Audio, Training, and Inference Using Google Colab.
## Leave A Star if This Repo Was Helpful
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R7AH1FA)
<a href="https://trakteer.id/ardha27">
    <img src="https://cdn.trakteer.id/images/embed/trbtn-red-1.png" alt="Trakteer" height="35">
</a>
<h3>Please add this code in dependencies to avoid the error while running the reference stage</h3>
<code>!pip install pyworld==0.3.2</code>
### Tutorial (Indonesian)
- https://youtu.be/mcbz_n6_w_A (v1)
- https://youtu.be/Rnp8DzH7G_k (v2)
<h3>The depedencies code should look like this:</h3>
<code>
    #@title Install Depedencies
%cd /content
!apt-get -y install build-essential python3-dev ffmpeg
!pip install pyworld==0.3.2
!pip3 install --upgrade setuptools wheel
!pip3 install --upgrade pip
!pip3 install faiss-gpu fairseq gradio==3.34.0 ffmpeg ffmpeg-python praat-parselmouth pyworld numpy==1.23.5 numba==0.56.4 librosa==0.9.2</code>
<br/>

### Download Youtube WAV and Splitting Audio (Stored in GDrive)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ardha27/AI-Song-Cover-RVC/blob/main/Download_Youtube_WAV_and_Splitting_Audio.ipynb)

### Training and Inference (Stored in GDrive)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ardha27/AI-Song-Cover-RVC/blob/main/RVC_Training.ipynb)

### Training and Inference V2.0 (Stored in GDrive)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ardha27/AI-Song-Cover-RVC/blob/main/RVC_TrainingV2.ipynb)
