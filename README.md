# Sleep-stage scoring from physiological signals

A KTH CM2013 three-person team project to classify 30-second sleep epochs as Wake, N1, N2, N3 or REM using EEG, EOG and EMG recordings.

## What we built

We developed a pipeline for signal preprocessing, artifact handling, time- and frequency-domain feature extraction, and feature selection. We evaluated k-nearest neighbors, SVM and Random Forest classifiers, using leave-one-subject-out validation to test performance on held-out subjects. Confusion matrices helped us examine errors between sleep stages.

## My contribution

I worked on EEG/EOG preprocessing and feature extraction, ran SVM experiments, produced evaluation figures and confusion matrices, and wrote the Results and Interpretation sections of the report. The team collaborated across the pipeline.

## Scope

This was a course research prototype, not a clinical device. The dataset was modest, and the N1 sleep stage remained difficult to classify. Team code, recordings and the report are not published here.

[CM2013 course materials and project scaffold](https://github.com/farhad-abtahi/CM2013)
