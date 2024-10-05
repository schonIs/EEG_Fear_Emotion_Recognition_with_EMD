# EEG_Fear_Emotion_Recognition_with_EMD
This is a code for the study of "EMD-Based Feature Extraction Toward Real-Time Fear Emotion Recognition Application Using EEG".

URL:https://ieeexplore.ieee.org/document/10417245  
2024 IEEE/SICE International Symposium on System Integration (SII) 8-11 Jan. 2024

Abstract:  
In recent years, many researchers have shown interests in EEG-based emotion recognition for the application of Brain Computer Interface devices. Therefore, this study investigates the applicability of Empirical Mode Decomposition (EMD)-based feature extraction method for real-time EEG fear emotion recognition. In this study, instead of relying on publicly available datasets such as the DEAP dataset, the EEG data are collected independently by utilizing video clips available on the Internet to elicit fearful emotions. The algorithm mainly consists of two parts: feature extraction and fear emotion recognition. In the feature extraction stage, the acquired EEG signals are divided into five seconds segments and decomposed into several Intrinsic Mode Functions (IMFs) using EMD. Subsequently, the mean and Differential Entropy are extracted from the first five IMFs. These features are then classified by Support Vector Machine. To investigate the applicability of EMD, the EMD-based feature extraction method is compared to conventional methods, namely Short-time Fourier Transform and Wavelet Transform. As a result, the EMD-based method has demonstrated superior accuracy in both subject-dependent and subject-independent classification compared to the other two methods.
