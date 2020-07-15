# HeartPulseProcessor
Tackling http://www.peterjbentley.com/heartchallenge/, also at https://www.kaggle.com/kinguistics/heartbeat-sounds

### Background
##### Heart Sound Segmentation

The first challenge is to produce a method that can locate S1(lub) and S2(dub) sounds within audio data, segmenting the Normal audio files in both datasets. To enable your machine learning method to learn we provide the exact location of S1 and S2 sounds for some of the audio files. You need to use them to identify and locate the S1 and S2 sounds of all the heartbeats in the unlabelled group. The locations of sounds are measured in audio samples for better precision. Your method must use the same unit.

##### Heart Sound Classification

The task is to produce a method that can classify real heart audio (also known as “beat classification”) into one of four categories for Dataset A:

- Normal
- Murmur
- Extrasystole
- Artifact (misc. other sounds)

and three classes for Dataset B:

- Normal
- Murmur
- Extrasystole

### Navigating Files

**ts_A**: file containing set of extracted features for all labelled data

### Important Notes on Commits
Commits: Basic Properties: Sample file used: ../input/heartbeat-sounds/set_b/normal__170_1307970562729_B.wav
