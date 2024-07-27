# A Role of Machine Learning in Human Stress
## step 1
### install python 3.7.0
## install pip libraries
#### pip install numpy==1.18.1
#### pip install matplotlib==3.1.3 
#### pip install pandas==0.25.3 
#### pip install opencv-python==4.2.0.32
#### pip install keras==2.3.1 
#### pip install tensorflow==1.14.0 
#### pip install h5py==2.10.0 
#### pip install protobuf==3.16.0
#### pip install pillow==7.0.0
#### pip install sklearn-genetic==0.2
**This are only few libraries to know full library list contact me on nanipitla555@gmail.com or 7981619641**


 
## step 2
### open python in cmd
### import nltk
### download.nltk()


## step 3
### copy the file loaction and past in the cmd with folder name with py extension

## step 4
### To run project double click on ‘run.bat’ file to get below screen
<img width="1280" alt="Screenshot 2024-07-27 at 9 11 46 PM" src="https://github.com/user-attachments/assets/b2195c9c-fe2f-43c9-afc9-e9e96829c74a">

 ### In above screen click on ‘Upload Tweets Dataset’ button to load dataset

 <img width="1280" alt="Screenshot 2024-07-27 at 9 12 13 PM" src="https://github.com/user-attachments/assets/ff31cc76-f994-4a80-aa1e-fcc8892d4a5f">

### In above screen select ‘stress_tweets.csv’ dataset and then click on ‘Open’ button to load dataset and to get below screen

<img width="1280" alt="Screenshot 2024-07-27 at 9 12 44 PM" src="https://github.com/user-attachments/assets/b12a5148-e407-4899-aa21-71c4973ad373">

### In above screen dataset contains total 10314 tweets and all tweets contains 30790 words and total unique words are 83 and application using 8973 records for training and 1341 for testing. Now both train and test data is ready and now click on ‘Run SVM Algorithm’ button to trained data using SVM machine learning algorithm.

<img width="1280" alt="Screenshot 2024-07-27 at 9 13 09 PM" src="https://github.com/user-attachments/assets/fa0d7bc0-8859-4db1-b8a3-469b922959dd">

### In above screen random forest got 97.68 correctly prediction accuracy and now click on ‘Predict Stress’ button and upload test file which contains tweets and by analysing those tweets machine learning algorithm will predict whether tweets contains any stress data or not. Below is the screen shots of test tweets which we upload in next screen

<img width="1280" alt="Screenshot 2024-07-27 at 9 13 19 PM" src="https://github.com/user-attachments/assets/42adcdb6-fcee-47d7-bf3c-ea5b3be3906d">

### In above screen uploading ‘test.csv’ file and now click on ‘Open’ button to predict stress

<img width="1280" alt="Screenshot 2024-07-27 at 9 13 26 PM" src="https://github.com/user-attachments/assets/4ede9ba4-cc0f-4db9-bbb2-4163b5696a2d">

### In above screen beside each tweet we can see predicted result as Stressed or Not stressed. From above screen we can see application detecting stress successfully from messages and now click on ‘Accuracy Graph’ button to get below comparison graph

<img width="1280" alt="Screenshot 2024-07-27 at 9 13 35 PM" src="https://github.com/user-attachments/assets/329db1e4-77a7-4923-80b3-6863873f4429">

### In above x-axis represents algorithm name and y-axis represents accuracy of those algorithms and from above graph we can say random forest is better than SVM
