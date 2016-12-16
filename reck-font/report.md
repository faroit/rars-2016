# Reproduction of "Tempo Estimation for Music Loops and a Simple Confidence Measure"

This is a reproduction of the paper "Tempo Estimation for Music Loops and a Simple Confidence Measure" with only the FSL4 database used.

## Requirements

### System Setup

-OS:	Ubuntu 16.04.1 LTS

-Python 2.7.12

### Software needed
-Ffmpeg

-Octave

-Vlc

-ReKordBox

## Installation

To install the codebase published with the paper, run

    git clone git@github.com/some/paper.git
    cd paper/
    pip install -r requirements.txt

## Instructions

### Download Dataset and preprocess data

   ./download.sh

### Preprocess Dataset

   ./data_preprocessing.sh

### Analyse Dataset   

   ./run_analysis.sh

### Evaluation

   ./run_analysis.sh


 The resulting figure `output.png` can be seen on page two of the paper.


## Evaluation

 During the evaluation of the paper *Title* I came across the following issues: