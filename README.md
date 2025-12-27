README

Nellai Dialect Automatic Speech Recognition System (Nellai-ASR)
Automatic Speech Recognition (ASR) system tailored for the Nellai / Tirunelveli Tamil dialect — a low-resource dialect of Tamil. Converts spoken audio in the Nellai dialect into written text with support for model training, evaluation, and inference.


 Overview

Automatic Speech Recognition (ASR) converts spoken language into readable text. While mainstream ASR systems exist for resource-rich languages, dialects like Nellai Tamil lack public datasets and tailored models. This repository provides tools, scripts, and training pipelines to build and evaluate an ASR system specifically for the Nellai dialect.

* Supports data preprocessing
* Model training & fine-tuning (Lora adapted Whisper model)
* Evaluation & inference pipelines
* Example scripts and baseline performance


Purpose
* ASR system tailored for the Nellai / Tirunelveli Tamil dialect (low-resource dialect)
* Converts spoken audio into text
Features
* Data preprocessing pipeline
* Training & fine-tuning scripts
* Evaluation with metrics like WER/CER
* Inference for real-time transcription
Structure
* Organised folders for raw/processed data, models, scripts, and notebooks
Usage Steps
1. Clone repository
2. Prepare dataset (audio + transcripts)
3. Install dependencies
4. Preprocess data
5. Train model
6. Evaluate performance
7. Run inference
Metrics
* Word Error Rate (WER)
* Character Error Rate (CER)
Examples
* GoogleColab notebooks for interactive demos
License
* MIT License

