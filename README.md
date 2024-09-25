**Multi-task Deep Learning for Age, Gender, and Race Estimation**

**Overview**
This repository contains the code for a multi-task deep learning project designed to           simultaneously predict age, gender, and race from human facial images. By using various deep   learning architectures such as EfficientNet B3, MobileNet V2, MobileNet V3, and a custom CNN, the aim is to evaluate and compare their effectiveness in multi-task learning scenarios.

**Project Motivation**
Predicting age, gender, and race accurately from facial images has practical applications in industries like marketing, forensics, and personalization. Although humans find it straightforward, building robust and efficient models for computers is a challenging task. This is mainly due to the complexity of variations in facial expressions, lighting, occlusions, and other external factors.

This project explores the multi-task learning paradigm, which allows the model to share learning across tasks, leading to improved generalization and reduced bias compared to models trained independently for each task.

**Architectures Explored**

The project focuses on four key architectures:

1.Custom CNN
2. MobileNet V2
3. MobileNet V3
4. EfficientNet B1

Each model is modified with three prediction heads for age, gender, and race estimation. These heads work together to capture nuanced facial features and improve prediction performance.

**Features**
Simultaneous Age, Gender, and Race Prediction: Models that handle all three tasks in one go.
Multi-Architecture Comparison: Explore and compare the performance of different architectures.
Custom Model Adjustments: Tailored architectures with specialized heads for each prediction task.
Practical Application Focus: Bridging the gap between theoretical research and real-world application with insights for industries.

**Key Findings**
Through thorough experimentation, it has been observed that:

Multi-task learning improves individual task performance by enabling the model to learn shared representations for age, gender, and race.
Modern architectures like MobileNet V3 and EfficientNet B3 outperform older models in terms of accuracy and efficiency, making them suitable for deployment in resource-constrained environments like retail or mobile devices.
