<!-- # Smart-Lighting -->
# Automated Street Lights & Enhanced Security System

## Overview
This system integrates automated street lights and an advanced security solution to enhance energy conservation and public safety in urban spaces.

## Features
- **Automated Street Lights**: Utilizes motion sensors and LED technology for energy-efficient illumination.
- **Energy Efficiency**: Activates lights only when needed, reducing power consumption.
- **Maintenance**: Self-diagnostic capabilities minimize maintenance requirements.
- **Adaptability**: Adjusts illumination based on environmental conditions.

- **Security Solution**: Initiates audio recording on a button press.
- **Real-time Processing**: Swiftly analyzes audio for distress words.
- **Automated Alerts**: Notifies authorities upon detecting alarming phrases.

## Benefits
- **Energy Conservation**: Reduces energy consumption and operational costs.
- **Enhanced Safety Measures**: Swift response to potential threats or emergencies.
- **Privacy Protection**: Selectively triggers alerts based on specific distress signals, respecting privacy.

## Conclusion
This system revolutionizes urban infrastructure, promoting energy efficiency and bolstering public safety. It's a testament to technology's potential in addressing societal concerns for a safer, more sustainable future.

### Tech Stack:
- **Automated Street Lights**: Motion Sensors, LED Technology
- **Security Solution**: Audio Recording, Real-time Processing, Voice Recognition

## ML Model
The above code uses PVCheetah API for audio to text transcription and then uses a simple logistic regression model for inference. The logistic regression model is limited by the lack of datasets for correct distress classification and might give random outputs for them. Currently a 4-gram model is used for the vectorization of the sentences. The hardware interface of the project is in the MAIN.txt and Library.txt files, and is still under development.