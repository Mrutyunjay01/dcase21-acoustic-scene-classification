# DCASE 2021 TASK 1A: Low-Complexity Acoustic Scene Classification with Multiple Devices

# Description

[TAU Urban Acoustic Scenes 2020 Mobile Development dataset](https://doi.org/10.5281/zenodo.3819968) is used as development dataset for this task.

This subtask is concerned with the basic problem of acoustic scene classification, in which it is required to classify a test audio recording into one of ten known acoustic scene classes. This task targets generalization properties of systems across a number of different devices, and will use audio data recorded and simulated with a variety of devices. Recordings in the dataset were made with three devices (A, B and C) that captured audio simultaneously and 6 simulated devices (S1-S6). Each acoustic scene has 1440 segments (240 minutes of audio) recorded with device A (main device) and 108 segments of parallel audio (18 minutes) each recorded with devices B,C, and S1-S6. The dataset contains in total 64 hours of audio. For a more detailed description see [DCASE Challenge task description](http://dcase.community/challenge2020/task-acoustic-scene-classification).

The task targets low complexity solutions for the classification problem in terms of model size, and uses audio recorded with a single device (device A, 48 kHz / 24bit / stereo). The data for the dataset was recorded in 10 acoustic scenes which were later grouped into three major classes used in this subtask. The dataset contains in total 40 hours of audio. For a more detailed description see [DCASE Challenge task description](http://dcase.community/challenge2020/task-acoustic-scene-classification).

Classifier complexity for this subtask is limited to 128 KB size for the non-zero parameters. This translates into 32K parameters when using float32 (32-bit float) which is often the default data type (32000 parameter values * 32 bits per parameter / 8 bits per byte = 128000 bytes = 128 KB). See detailed description how to calculate model size from [DCASE Challenge task description](http://dcase.community/challenge2020/task-acoustic-scene-classification).

# References

## DCASE'20 
- Acoustic Scene Classification in DCASE 2020 Challenge: Generalization Across Devices and Low Complexity Solutions [paper](http://dcase.community/documents/workshop2020/proceedings/DCASE2020Workshop_Heittola_56.pdf)
- Audio Tag Representation Guided Dual Attention Network for Acoustic Scene Classification [paper](http://dcase.community/documents/workshop2020/proceedings/DCASE2020Workshop_Kim_34.pdf) [video](https://www.youtube.com/watch?v=2OfwZsw11eg)
- Low-Complexity Models for Acoustic Scene Classification Based on Receptive Field Regularization and Frequency Damping [paper](http://dcase.community/documents/workshop2020/proceedings/DCASE2020Workshop_Koutini_91.pdf) [video](https://www.youtube.com/watch?v=dlgbN6Leiwg)
- Embedded Acoustic Scene Classification for Low Power Microcontroller Devices [paper](http://dcase.community/documents/workshop2020/proceedings/DCASE2020Workshop_Naccari_44.pdf) [video](https://www.youtube.com/watch?v=7wY0Qmy3BF8)
- Ensemble of Pruned Low-Complexity Models for Acoustic Scene Classification [paper](http://dcase.community/documents/workshop2020/proceedings/DCASE2020Workshop_Ooi_24.pdf) [video](https://www.youtube.com/watch?v=CiaBpajZLDU)
- Lightweight Convolutional Neural Networks on Binaural Waveforms for Low Complexity Acoustic Scene Classification [paper](http://dcase.community/documents/workshop2020/proceedings/DCASE2020Workshop_Pajusco_63.pdf) [video](https://www.youtube.com/watch?v=rBSkp6mIEmE)
- Acoustic Scene Classification with Spectrogram Processing Strategies [paper](http://dcase.community/documents/workshop2020/proceedings/DCASE2020Workshop_Wang_58.pdf) [video](https://www.youtube.com/watch?v=p-p8uvJceBc)
- Searching for Efficient Network Architectures for Acoustic Scene Classification [paper](http://dcase.community/documents/workshop2020/proceedings/DCASE2020Workshop_Wu_18.pdf) [video](https://www.youtube.com/watch?v=xToANK4B4LQ)
## Datasets
- TAU Urban Acoustic Scenes 2020 Mobile, Development dataset [link](https://zenodo.org/record/3819968#.YEpO9mgzZEY)
- A multi-device dataset for urban acoustic scene classification [paper](https://arxiv.org/pdf/1807.09840)