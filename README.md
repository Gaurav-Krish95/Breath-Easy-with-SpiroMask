# Spiromask Project: A Sonic Journey into Lung Function
## Introduction
Welcome, fellow explorers of the human body! I, Gaurav, invite you on a unique expedition – a deep dive into the captivating world of lung function using an innovative tool known as the Spiromask.
Our mission? To unveil the secrets of breathing, the very essence of life. Buckle up as we venture into the intricate details of differentiating breathing rate from sampling rate – a crucial aspect in understanding lung health.
## Tools of the trade

## 1. Audacity
Are trustworthy companion on this journey is audacity,a powerful audio recording software. With its help we will capture the symphony of breaths inhalation, and exhalations.

## 2. The Launchpad
My trusty laptop serves as our launchpad. Its keys hum with anticipation, ready to record every nuance of our sonic exploration.

## 3. My Voice
As your guide, my voice will lead us through this auditory adventure. Listen closely – each breath holds a story waiting to be told.

# The Goal
As you relax and listen, remember that our purpose transcends mere entertainment. We seek valuable insights into lung function. Let the symphony guide you deeper, beyond the surface – where science and creativity harmonize.

## 1. Loading Spiromask symphony
I have recorded via audacity but I exported audacity project to WAV Format then i uploaded my audio into soundcloud you can navigate to the give link below.
`Listen to the Spiromask Symphony`Below and sitback and relax with music and hum of enviorment.
```html
https://on.soundcloud.com/9yiF5
```

## 2. Sampling rate of recorded audio & breathing frequency range 
our goal is to find sampling rate of audio which is clearly shows in audacity software under dropdown menu which is Stereo, 44100Hz 32bit-float and for finding frequency range we have to plot spectogram but before plotting we have to set high-pass filter for getting accurate rejult and precisie band of frequency to navigate.
## 3. Plotting spectogram
we have to select dropdown menu in left at Audio 1 and select 'spectogram' to convert waveform to spectogram
## 4. Finding frequency range
in spectogram vertical axis represents frequant in hz and horizontal axis represnt time, range of Hz is from 0 to 10000. so first we have to convert our breathing rate into frequency and then we have to navigate to vertical axis.
for this normal human breathing is 12-24 breaths/min which means 12-24 breaths/second which is 0.2-0.4Hz in frequency.
so we will zoom in to find contrastic colours from spectogram which is our breathing rate, but because audacity can not go into very presise value, I have to increase frequency range from 10 to 100 hz

# Contributors
- [Gaurav](https://github.com/Gaurav-Krish95)🌬️🎶
## 🔗 connect on

- [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://in.linkedin.com/in/gourav-kumar-8b7538232/)

# Screenshots 

## Setup of settings in audacity
#### First after recording in audacity, we have to filter higher frequencies from high pass filter for that apply 20Hz for precision and then we have to plot spectogram to observe frequency range[ y-axis is frequency and x-axis is representing time ]
- ![1](https://github.com/Gaurav-Krish95/Breath-Easy-with-SpiroMask/assets/161487912/4d7519f5-5652-479b-be6f-3a0ae45cd801)
- ![2](https://github.com/Gaurav-Krish95/Breath-Easy-with-SpiroMask/assets/161487912/c77bd7dc-ce9f-470d-80cd-b01feb8dae25)
- ![3](https://github.com/Gaurav-Krish95/Breath-Easy-with-SpiroMask/assets/161487912/aea87dd0-e8bc-4458-9e49-fa5aefea4b99)
#### Humans have breath per min is from range of 12 to 24 breath per min (0.2 to 0.4 Hz) so we will zoom out to vertical axis because it represents freuency in hz
- ![4](https://github.com/Gaurav-Krish95/Breath-Easy-with-SpiroMask/assets/161487912/5ba82d76-3eb8-4135-b01b-c679f9ffda6c)
#### we can't measure accurately from spectogram so we have to zoom out to observe strips with constant contrast is breathing frequency
- ![5](https://github.com/Gaurav-Krish95/Breath-Easy-with-SpiroMask/assets/161487912/9772f771-9840-4309-8e86-eacaf7a07c8d)
- ![6](https://github.com/Gaurav-Krish95/Breath-Easy-with-SpiroMask/assets/161487912/27820283-a81b-44a8-9ffe-73888fcbef2b)
- ![7](https://github.com/Gaurav-Krish95/Breath-Easy-with-SpiroMask/assets/161487912/11d7f0d9-46f5-4a33-a5b1-3540222cc3ea)
- ![8](https://github.com/Gaurav-Krish95/Breath-Easy-with-SpiroMask/assets/161487912/98da2b06-bb7e-4b76-9e41-2f13ad292e75)

# Rejult:
-Sampling rate of audio = Stereo, 44100Hz 32bit-float
-I applied high pass filter of 20hz
-We can't get accurate rejult from audacity because of its limitation, so we have to understand via spectogram.

