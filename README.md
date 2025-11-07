# Forced Alignment using Montreal Forced Aligner (MFA)

This repository contains the process and output of performing forced alignment on a set of speech recordings using the *Montreal Forced Aligner (MFA). The output TextGrid files were inspected using **Praat* to analyze phoneme and word-level alignments.

## Repository Structure


wavs/               # Contains audio (.wav) and transcript (.txt/.lab) files
textgrids/          # MFA output TextGrid alignment files
README.md           # Project documentation (this file)


## Requirements

* *Conda / Miniconda*
* *Montreal Forced Aligner (MFA)* installed in a conda environment
* *Praat* for alignment inspection

## Setup Instructions

### 1. Create and Activate MFA Environment

bash
conda create -n mfa python=3.10
conda activate mfa


### 2. Install Montreal Forced Aligner

bash
conda install -c conda-forge montreal-forced-aligner


### 3. Dataset Preparation

* Store .wav files and corresponding .txt transcript files in the same folder (wavs/)
* Ensure transcript files contain clean text (no punctuation or special characters)

### 4. Run Alignment

bash
add ur file path\


### 5. Output Files

The aligned TextGrid files will be generated here:


add ur file path 


## Inspecting Alignments in Praat

1. Open *Praat*
2. Read > Read from file... → Select .wav
3. Read > Read from file... → Select corresponding .TextGrid
4. View & Edit
5. Inspect *word* and *phoneme* tier boundaries

## Observations

* Word boundaries aligned correctly
* No significant timing or phoneme boundary errors observed

## Author

Apurva Hanumanthu
