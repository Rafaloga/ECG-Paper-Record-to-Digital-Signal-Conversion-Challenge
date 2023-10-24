# ECG-Paper-Record-to-Digital-Signal-Conversion-Challenge
This challenge involves developing an image processing algorithm using \textit{OpenCV} or similar libraries to convert ECG paper records into digital signals. The process includes image preprocessing to enhance quality, extracting ECG traces from various layouts, and digitizing these traces. The provided dataset contains diverse ECG paper record images. The solution encompasses reading, preprocessing, segmentation, and digitization, enabling the conversion of paper records into digital ECG data.

## Introduction
This work is centered around a critical challenge in healthcare: the conversion of paper-based electrocardiogram (ECG) records into digital ECG signals. This task is essential for making the data accessible for more advanced digital processing and analysis. The work has been divided into three fundamental stages, each of which contributes to the success of the conversion process.

In the first phase, an "Image Preprocessing" step has been carried out. Here, the initial step involves reading the ECG record image and applying a series of techniques, filters, and transformations. The primary goal is to enhance the quality and clarity of the image. This enhancement not only aids in visual interpretation but also lays the foundation for the subsequent separation of the signal into various traces that will be digitized.

The second part of this project focuses on the extraction of ECG traces. This stage is critical for automation. Specific image processing techniques designed for these kind of problems are employed. The outcome is the automatic identification and separation of individual traces, for the different images presented in the studied dataset.

Finally, the third stage involves transforming the original signal into a digital representation. This is achieved through a digitization process that includes filtering the original signal. In the third stage, filtering and resizing not only simplifies the storage of the signal in digital format but also ensures that the signals are in the same format, making it easier to compare them and reproduce the information contained in the original paper record.

These three phases come together to create an automated system that effectively converts paper-based ECG records into digital ECG signals, enabling their access and advanced analysis in healthcare settings.

In addition to these three phases, I have undertaken the development of the Bonus section of the Challenge. This final segment has been divided into two distinct parts. 
Firstly, I've created a simple web application equipped with a friendly user interface. Within this application, users can effortlessly upload images of ECG paper records. The application leverages the code developed during the preceding three phases to perform pre-processing, trace extraction, and signal digitization, and allows users to obtain the digitizated singal and download it.

Moving on to the second part, I researched various deep learning techniques aimed at enhancing the tool's performance. Specifically, my focus was on image segmentation algorithms, especially those pretrained with databases of scanned documents, as I wanted to try a different approach on the trace extraction. However, despite these efforts, the results obtained failed to meet the desired level of improvement and did not surpass the performance achieved with the earlier version of the application. The primary challenge stemmed from the lack of specialized models and data tailored to this specific problem, ultimately limiting the efficacy of these more advanced techniques in enhancing the tool's accuracy.

## Original Image & Digitizated Signal Obtained
<p align="center">
  <img src="https://github.com/Rafaloga/ECG-Paper-Record-to-Digital-Signal-Conversion-Challenge/assets/99535533/78bf2091-9f46-40e9-9880-52d6378260fc" width="45%" />
  <img src="https://github.com/Rafaloga/ECG-Paper-Record-to-Digital-Signal-Conversion-Challenge/assets/99535533/96d144a3-45b2-4575-9aee-b19011d5c660" width="45%" /> 
</p>
