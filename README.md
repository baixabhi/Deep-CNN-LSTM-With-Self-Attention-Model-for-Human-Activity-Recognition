# Human Activity Recognition Using Wearable Sensors and Deep Learning

Human activity recognition (HAR) is a challenging problem with diverse applications in daily life, ranging from healthcare to fitness tracking. Traditional methods rely on either video image recognition or wearable sensors. While wearable sensors offer portability and convenience, their effectiveness in HAR remains uncertain. To address this, this project introduces a novel deep learning model that combines convolutional neural networks (CNNs) and long short-term memory (LSTM) networks with self-attention.

## Overview

My proposed model aims to accurately recognize human activities such as standing/sitting, regular walking, running, and jogging, using data collected from smartphone sensors. Leveraging the MHEALTH dataset, our model achieves remarkable accuracy, boasting a rate of 98%.

## Methodology

### CNN-LSTM Architecture

This model extracts features from time-series sensor data using CNNs and LSTMs. CNNs are employed for spatial feature extraction, capturing patterns from sensor data. LSTM networks handle temporal dependencies, enabling the model to understand sequences of sensor readings effectively.

### Self-Attention Mechanism

To enhance predictive capabilities, we introduce a self-attention mechanism. This mechanism allows the model to focus on relevant parts of the input sequence, improving its ability to discern subtle patterns crucial for activity recognition.

## Results

The proposed model demonstrates superior performance in human activity recognition. By effectively combining CNNs, LSTMs, and self-attention, it achieves an accuracy rate of 98% on the MHEALTH dataset. These results underscore the efficacy of our approach in accurately identifying various human activities.

## Potential Applications

The developed model holds significant potential in clinical settings, where accurate activity recognition is crucial for monitoring patient health and rehabilitation progress. Additionally, it can find applications in fitness tracking, personalized coaching, and various other domains requiring precise activity monitoring.

## Conclusion

In conclusion, this study presents a novel approach to human activity recognition using wearable sensors and deep learning techniques. By leveraging the power of CNNs, LSTMs, and self-attention, our model delivers impressive accuracy and holds promise for further advancements in HAR systems. We believe that our findings provide a strong foundation for future research aimed at enhancing the accuracy and efficacy of activity recognition systems.
