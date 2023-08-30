# Parkison Disease

## Project and Data Brief

Diagnosing Parkinson’s Disease using voice sample data analysis
According to the U.S. National Institute of Neurological Disorders and Stroke, Parkinson’s Disease (PD) is a ‘movement disorder of the nervous system that gets worse over time’.1 Common symptoms include tremors, rigidity, bradykinesia, and postural instability. Notable figures who suffered from PD include the legendary boxer Muhammad Ali, the former U.S. president George H.W. Bush, the Back to the Future actor Michael J. Fox, the heavy metal legend Ozzy Osbourne, and the late Pope John Paul II.2 Sadly, there is currently no known cure for PD. There are also no specific diagnostic tests for the disease. Blood and laboratory tests, as well as brain scans, have been used to rule out other disorders that may cause the symptoms. These diagnostics are invasive with rigorous procedures that may potentially cause further stress for a person living with Parkinson’s Disease (PPD).
There is growing interest in developing new, non-invasive methods for diagnosing PD. One possible approach is to analyse a person’s speech data obtained from multiple types of sound recordings. PPD usually experiences dysphonia, which leads to reduced loudness, breathiness, roughness, and exaggerated vocal tremors. These symptoms can be diagnosed in a non-invasive way by analysing various frequency-based characteristics in a person’s voice.
This group assessment project focuses on analysing a set of acoustic measurement data extracted from the voice samples of PPD and, where indicated, from those who were healthy. For these subjects, physicians also carried out medical examinations on the PPD and assigned them an appropriate Unified Parkinson’s Disease Rating Scale (UPDRS) score to indicate the disease severity and progression.

##### 1 National Institute of Neurological Disorders and Stroke (2023). https://www.ninds.nih.gov/health- information/disorders/parkinsons-disease

##### 2 https://www.parkinson.org/understanding-parkinsons/statistics/notable-figures

### Variables of PD

- Subject identifier
- Jitter %
- Jitter ms
- Jitter r.a.p
- Jitter p.p.q.5
- Jitter d.d.p
- Shimmer %
- Shimmer dB
- Shimmer a.p.q.3
- Shimmer a.p.q.5
- Shimmer a.p.q.11
- Shimmer d.d.a
- Harmonicity (autocorrelation)
- Harmonicity NHR
- Harmonicity HNR
- Median Pitch
- Mean Pitch
- SD Pitch
- Minimum Pitch
- Maximum Pitch
- Pulse (no)
- Pulse (No. of periods)
- Pulse (mean period)
- Pulse (SD period)
- Voice (unframed voice)
- Voice (no. of breaks)
- Voice (degree of breaks)
- UPDRS
- PD indicator

### Dataset

This dataset contains data collected from 40 study subjects, of which 20 were individuals living with Parkinson’s Disease (PPD) and the remaining 20 were healthy individuals (non-PPD group).3 The mean age of the PPD group is 64.86 years old (standard deviation: 8.97). The mean age of the non-PPD group is 62.55 years old (standard deviation: 10.79).
In this study, each subject was asked to record 26 different voice samples. These samples include the recording of saying 3 sustained vowels (“a”, “o”, “u”), 10 numbers (1 to 10), 9 different words, and 4 rhymed short sentences. This dataset includes all these voice samples but does not indicate the specific recording it represents (i.e. we do not know whether a voice sample comes from recording a sustained vowel or a short sentence). Please note this limitation.
A set of 26 acoustic features were further extracted from each voice sample using a free acoustic analysis software called Praat.4 The variables in this dataset represent these features.

### Correlation matrix

![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/heatmap.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Harmonicity_autocorrelation.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Pulse_Mean_period.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Median_pitch.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Harmonicity_NHR.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Jitter_r.a.p.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Jitter_p.p.q.5.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Shimmer_a.p.q.11.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Voice_degree_breaks.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Pulse_No.Periods.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Shimmer_a.p.q.3.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Voice_no.Of_breaks.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Pulse_SD_Period.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Mean_pitch.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Maxmium_pitch.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Shimmer_a.p.q.5.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Jitter%.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Shimmer%.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/SD_pitch.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Pulse_no.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Voice_Unframed_voice.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Jitter_d.d.p.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Shimmer_dB.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Minimum_pitch.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Shimmer_d.d.a.png)
![alt text](https://github.com/bibekdhakal/parkison-disease-stat/blob/nstha/output/Jitter_ms.png)

