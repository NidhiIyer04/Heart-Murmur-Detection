# Heart-Murmur-Detection
Heart murmur detection involves identifying abnormal sounds during a heartbeat, known as murmurs, which can indicate various cardiovascular conditions. These murmurs are typically detected through auscultation, where a healthcare professional listens to the heart using a stethoscope. The detection process often involves analyzing heart sound recordings, which can be captured using phonocardiograms or digital stethoscopes.

Murmurs are classified based on their timing (systolic or diastolic), pitch, intensity, and location within the heart. Advanced methods, such as machine learning and signal processing techniques, are increasingly used to automate the detection and classification of heart murmurs from audio recordings. This approach aids in early diagnosis and monitoring of conditions such as valve diseases, congenital heart defects, and other cardiac issues, improving patient care and treatment outcomes.

## Datasets being used:
- 2022 Physionet Challenge data: https://moody-challenge.physionet.org/2022/ 
- 2016 Physionet Challenge data: https://physionet.org/content/challenge-2016/1.0.0/

## Progress:
1. Downloaded 2016 challenge data and 2022 challenge data.
2. Decided to follow a semi supervised model since only the 2022 challenge has labeled data.
3. Divided all labeled data to training and validation set and added unlabeled data into testing set.
4. Processed a total of 2216 training, 947 validation, and 3240 testing heart sound recordings.
