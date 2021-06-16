# Doctor-App

### Abstract
In this Project our main focus on the problem statement given by Manipal Hospitals is that the patient should be able to book appointments and chat with Doctors in the concerned field of study. In this we are going to design an android application for the Manipal Hospitals where they could use this application to manage the Doctor appointments and have a platform where the doctors and patients can communicate. 

The android application will be for the common public to access to the various Hospital Doctors of different fields of study according to their need and book an appointment and chat with doctors to help them in understanding the patients health. This application can also be used by the doctors where they can chat with their patients and give required prescription to their patients. 


### Introduction

Our project focus on the need for an app to create a platform for Doctors and Patients where they can communicate , book appointments and get their medicine prescription all in one single place.  
 
In our project we have an app where the patients can login or create an account in the app after which he/she can select any category of health issue for which they require a Doctors assistance. After that from a list of doctors they can select and chat with them to discuss about their issue. Patients can share images of their issue to help doctor understand their problem better. They can also view the medicine prescriptions provided by their doctor. 

We have a separate login for doctors where they can manage their patients,chat with them, book an appointment for them and also give prescription. 

### Methodology Used

#### Modules:
Our project Modules:

Android Application:


#### 1.1.  User Interface:
This includes designing the application that is easy to use and understand for the general public. It contains designing the xml for all the pages used in the app. 
      
#### 1.2. Login/ Signup: 
This module includes creating separate logins and signup functionality for both Doctors and Patients. The credentials will be verified by the firebase allowing an authentic login thus enabling a secure Login process. 

#### 1.3.  Database:
For creating the app we would require an online database which would be used in the Login/Signup functionality. It would also be required for having a list of Doctors in various fields, to store the individual chats , to store the appointments of patients under a particular doctor , to store the prescription given by the doctors. We have taken Firebase as our Database for the app. 
      
#### 1.4. Chat : 
A main functionality of our app is the chat application to help doctor and patient communicate among themselves to help understand each other better. We have include an option to share images so that patients can share images of their problems to help doctor understand better. A green signal will appear beside the doctor name if the doctor is currently logged into the application. 
	
#### 1.5. Prescriptions:
This module includes an added functionality where the doctor can send a medicine prescription instructing the patient about when to take the medicine. The patient can view this prescription in their application. 
      
#### 1.6. Appointments: 
This functionality will enable the patient to set an appointment with their doctor. The patient can chat with their doctor to decide a date for the appointment. The doctor can then set an appointment with the patient in his app. We use Google calendar for this functionality. 
      
      
### Block Diagram

Block diagram  for Android App login

<img width="706" alt="image" src="https://user-images.githubusercontent.com/45623734/122225309-926cf400-ced2-11eb-9b86-a0c61b2d11b0.png">
      
      
### App Screenshots

##### This is the login/signup Page for the Android app. The patient can login the app from login page or else the user can signup as a new user. Both Doctors and Patients have separate login. 

<img width="695" alt="image" src="https://user-images.githubusercontent.com/45623734/122225555-cc3dfa80-ced2-11eb-9a7e-49967190c64c.png">



##### Below is the screen shot for chat and appointment scheduling functionality. 

<img width="610" alt="image" src="https://user-images.githubusercontent.com/45623734/122225626-da8c1680-ced2-11eb-9fe3-26f7a31d8454.png">

##### Below is the screen shot for medicine prescription functionality. 
  
![image](https://user-images.githubusercontent.com/45623734/122226704-da404b00-ced3-11eb-90fa-4d6e8f82dea4.jpeg)
![image](https://user-images.githubusercontent.com/45623734/122226714-dca2a500-ced3-11eb-97bb-224a4e7ee2df.jpeg)
![image](https://user-images.githubusercontent.com/45623734/122226753-e4624980-ced3-11eb-8098-8b5751bd921a.jpeg)


##### Below is the screenshot of server side , this is the Firebase real-time database hierarchical view of the data stored. The data is store in JSON objects.  

![image](https://user-images.githubusercontent.com/45623734/122225747-f5f72180-ced2-11eb-9c3c-ef870591173a.png)


### Conclusion

The project was completed and our team successfully created our “DOCTOR APP”. We provided our users with various functionalities and an attractive UI for enhanced user experience. Our project helps many patients and doctors and provides them a platform to communicate, prescribe medicines, book appointments to help solve the problems faced by many Hospitals in providing all these needs. The Objective of our project was achieved with satisfaction.




