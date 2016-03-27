INTRODUCTION

The Chinese Speech Personality Corpus dataset includes the following material:

1) Audio files
2) Personality questionnaires
3) Personality assessments
4) Metadata

THE DATA

1) Audio files

The dataset includes 1925 audio clips of 10 seconds from 77 unique speakers.
XXXYY.wav (XXX: speaker ID, YY: clip No. of every speaker.)

Audio files directory: ./audio_clips
Audio files format: .WAV files(16 bit, mono, 8 kHz) 


2) Personality questionnaires

This dataset includes the  questionnaires filled individually
by the 77 speakers. The questionnaires correspond to the NEO-FFI
items, the answers range from "Strongly Disagree" (1) to
"Strongly Agree" (5).

Raw Personality Questionnaires directory: ./BFI_item_answers 
Raw Personality Questionnaires format: doc and txt


3) Personality assessments

The dataset includes the personality scores assigned individually. 
The scores are obtained from the raw personality questionnaires.
The five scores corresponds to the following traits:

Neuroticism
Extraversion
Openness
Agreeableness
Conscientiousness

Personality Assessments directory: ./personality_scores
Personality Assessments format: csv


4) metadata

The dataset includes metadata for each speaker:
gender ("M" for male and "F" for female)
speaker ID (integer between 1 and 322)

metadata directory: ./metadata
metadata format: txt