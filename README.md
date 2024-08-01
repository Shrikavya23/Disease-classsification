# Disease-classsification

## Introduction
COVID-19 is a highly infectious respiratory disease caused by the SARS-CoV-2 novel coronavirus. In COVID-19 patients, chest X-rays show signature patterns like patchy infiltrates, ground glass opacities and pulmonary consolidations indicating fluid buildup and inflammation. Identifying these early is key to isolation and care with oxygen support. Pneumonia is a common lung infection that inflames the alveoli in one or both lungs, filling them with fluid which appears as dense areas called consolidations on X-ray images. This makes breathing painful and limits oxygen intake leading to issues if not treated promptly with antibiotics and medications. Chest X-rays are commonly used to diagnose various lung conditions. Identifying conditions accurately through X-rays can guide critical treatment decisions and care for patients suffering from respiratory illnesses. Normal chest X-rays show clear, black lung fields with no areas of abnormal opacity, consolidation or other artifacts. Minor variations can appear based on factors like patient positioning but a trained radiologist can discern normal lungs from ones with pneumonic or COVID-19 infections.

## Objectives
* Collect public chest X-ray image datasets covering Normal, Pneumonia and COVID-19 cases for developing classification models.
* Employ data augmentation techniques like rotations and color shifts to expand the diversity of training data available.
* Develop a deep convolutional neural network architecture using transfer learning with the pre-trained VGG16 model for effective feature extraction.
* Train the classification model using binary cross-entropy loss function and Adam optimizer for 15 epochs monitoring model loss and accuracy.
* Evaluate the performance of the final model using test data accuracy, loss metrics, confusion matrix, and classification report to validate effectiveness.
