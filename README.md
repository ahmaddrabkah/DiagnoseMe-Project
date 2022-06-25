# DiagnoseMe-Project
DiagnoseMe is a web application used as a platform for patients to get their diagnosis by navigating through our provided 
list of illnesses that they think or may have, then they enter their medical info like age, gender, weight, calories, blood 
pressure,..etc. after that the application predict if they have the disease or not by using Machine Learning (ML). 
Basically, it helps patients to get their diagnosis in an elegant and easy way without the need to go to a hospital or doctor’s clinic.

# Implementation and Design
Our software contains three main parts Machine Learning (ML) models, web application and the User Interface (UI). Each part has been developed and implemented independently of the others parts using a programing language.
Following you could access the repository for each part : 
- [Machine Learning models](https://github.com/ahmaddrabkah/Models)
- [Web application](https://github.com/ahmaddrabkah/DiagnoseMe)
- [User Interface](https://github.com/ahmaddrabkah/DiagnoseMe-UI)

# Dataflow :
The using of the software and dataflow in the application is like the following 
1. Client open the website and navigate to disease he/she want to diagnose then start fill diagnose form with his/her medical data.
2. After client submit the diagnose form the UI will request the web app for the result which in turn call another app with client request data.
3. The app that called by web app will select the model that the client want to diagnose its disease and return the result to web app which will send it  to the UI.

![image](https://user-images.githubusercontent.com/87063938/175792256-145dc43e-d24e-4858-9ec7-ca4c83a7ce68.png)


# Documentation 
You will find the whole details and description of the project in the [Documentation](https://github.com/ahmaddrabkah/DiagnoseMe-Project/blob/main/Graduation_Project%20_Report2.pdf)

# Presentation
You could get a quick introduction and explanation of the project in the [Presentation](https://github.com/ahmaddrabkah/DiagnoseMe-Project/blob/main/Graduation-Project2-Presentation.pptx)


# Deployemnt 
The application has been deployed into Microsoft Azure so you could access it online : https://diagnoseme.team
