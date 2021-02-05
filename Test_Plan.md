# Overall Test Plan
The main purpose of our test is to observe whether each unit of the face mask recognition can work well，As a deep learning and face recognition project, from data selection and extraction to model training, fitting may be wrong. This test making any components in this project working well.
# Test Case Descriptions
## Data Selection Test 1
- DS1.1 This test will ensure data are clean, no strange data will be in the data set.
- DS1.2 This test will ensure that the data in dataset which selected are sufficient and feature-rich.
- DS1.3 This test will ensure image preprocess function works good.
## Training Process Test 2
- TP1.1 This test will choose the most suitable learning rate.
- TP1.2 This test will ensure update the data and labels lists function doing well.
- TP1.3 Split test on training set and test set to find the most suitable split ratio.
- TP1.4 Training image generator test.
- TP1.5 MobileNetV2 network test, ensuring the head FC layer sets are.
- TP1.6 Compile model test.
- TP1.7 Train the head of the network test.
- TP1.8 Predictions testing set test.
- TP1.9 Nicely formatted classification report test.
- TP1.10 Training loss and accuracy test.

# Test Case Matrix
| Name | Normal/Abnormal | Blackbox/Whitebox | Functional/Performance | Unit/Integration |
| --- | ---| --- | --- | --- |
| DS1.1 | Normal | Whitebox | Functional | Unit |
| DS1.2 | Normal | Whitebox | Functional | Unit |
| DS1.3 | Normal | Whitebox | Functional | Unit |
| TP1.1 | Normal | Whitebox | Functional | Unit |
| TP1.2 | Normal | Whitebox | Functional | Unit |
| TP1.3 | Normal | Whitebox | Functional | Unit |
| TP1.4 | Normal | Whitebox | Functional | Unit |
| TP1.5 | Normal | Whitebox | Functional | Unit |
| TP1.6 | Normal | Whitebox | Functional | Unit |
| TP1.7 | Normal | Whitebox | Functional | Unit |
| TP1.8 | Normal | Whitebox | Functional | Unit |
| TP1.9 | Normal | Whitebox | Functional | Unit |
| TP1.10 | Normal | Whitebox | Functional | Unit |
