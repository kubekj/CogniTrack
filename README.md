# CogniTrack 🎤🧠

AI-powered framework for early dementia detection through vocal biomarkers analysis. Research project investigating speech patterns indicating cognitive decline.

## Overview
Early detection of cognitive decline remains challenging due to the limited accessibility of traditional diagnostic methods. CogniTrack leverages machine learning and voice analysis to develop scalable, non-invasive screening solutions.

## Core Components
- Voice feature extraction pipeline
- ML models for cognitive assessment 
- Clinical validation framework
- Statistical analysis tools

## Project Structure
```
src/
├── preprocessing/    # Audio processing & feature extraction
├── models/           # ML model implementations
├── analysis/         # Statistical analysis tools
├── validation/       # Clinical validation framework
└── utils/            # Helper functions & utilities
```

## Setup
```bash
git clone https://github.com/kubekj/CogniTrack.git
cd CogniTrack
pip install -r requirements.txt
```

## Data
Uses Sonde Health dataset containing ~500 voice samples with demographic and health data. Data access requires appropriate permissions.

## Research Context
MSc Thesis project at the Technical University of Denmark (DTU) in collaboration with Sonde Health and GN Group.

## License
MIT
