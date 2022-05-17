# Acit4530 Data Mining at scale: Algorithms and systems "Human activity recognition using RNN"

This code and the project is created for a mandatory project Acit4530 Data Mining at scale: Algorithms and systems (https://student.oslomet.no/en/studier/-/studieinfo/emne/ACIT4530/2022/HØST) Master course at Oslo Metropolitan university. The data set for this project is taken from the link (http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) [1] . Similarly, the information of the data set can be found in details in the dame url. The data was collected using three different sensors; accelerometer, gyroscope and magnetometer that are build into IMU devices, and the smartphones to recognize the activity being performed by the user of the device. The HAR dataset has 6 activities with 30 volunteer with an age bracket of 19-48 years. The activies are walking, walking upstairs, walking downstairs sitting standing and lying.  Each of these activities are consists of 3D raw signals extracted from above mentioned 3 sensors [1]. There are 7352 training 2947 test samples in the dataset. This dataset also includes postural transitions that occur between the static postures: standing to sitting, sitting to standing, sitting to laying, laying to sitting, standing to laying, laying to standing

The signals samples were pre-processed by applying noise filters and sampled in fixed-width sliding windows of 2.56 sec with a 50 percent overlap (i.e. 128 readings/windows). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The activities of UCI-HAR data set with activities per data-points is shown in Figure 
![The number of data points per activity of HAR dataset.]datapoint_classification.pdf.  

















## Reference
[1]Anguita, D., Ghio, A., Oneto, L., Parra, X. & Reyes-Ortiz, J. L. A public domain dataset for human activity recognition using smartphones. In ESANN
(2013).
