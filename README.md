# 🩺Smart Planner

## 📃 Bachelor's Thesis - Computer Science, University of Bucharest, 2022

____



### ◻️ Abstract

​	Taking care of our health is one of the most important things we need to do. That's why any tool that helps us do this is of great benefit. This was the motivation behind the development of Smart Planner, an app that aims to optimize the process of managing medical appointments, for both patients and medical staff in charge.

​	Smart Planner is an Android app that streamlines the process of creating an appointment, gives patients access to useful information, notifies them of their appointments and introduces the concept of appointment switch.

​	The functionality of the application is diverse and adjusted to user needs. Users can login into the application with an existing account, with an account on a third party platform such as Facebook or Gmail, or register by filling in a form. Each user has a dedicated profile page where they can view and edit their personal details and also select a profile photo.

​	As a **patient**, the main screen displays all their appointments ordered by date, and can be filtered as past or future appointments or searched by title in a search bar. The patient can create a new appointment at the time, date, doctor and clinic of their choice depending on availability. They can add a corresponding event to their personal calendar with the necessary details filled in automatically. There is also a notifications page where the user can be notified of their appointments. In the appointment details page, the user has access to all the necessary information, can call the clinic directly from the app and share the appointment details in another app. Also available is a map showing the current location and a Marker with the location of the clinic which, when pressed, displays an information window with a button for calculating the recommended route between the two locations. On the Emergency page, if the patient is unable to keep an appointment due to unforeseen events, they can send a request to another patient who has an appointment at a convenient time so that they can make a change at their convenience. Thus, in the case of a busy period where rescheduling could take several weeks, patients can avoid this wait by interacting with other patients.

​	As an **administrator**, all the appointments of the clinic to which he/she is employed are displayed on the main page. On the details page of an appointment there are buttons for calling the patient or deleting the appointment. The admin can be redirected to the patient's details page and can ask the patient to fill in personal details if missing.

​	For implementation I chose to use the MVVM architecture which has the role of separating the application logic from the interface, so that the application has a stable and well defined structure. For the application screens I used activities and fragment to optimize the use of the resources that the application needs. Map integration was done with Maps SDK for Android, and the Directions API was used for calculating the recommended route between the patient's current location and the medical clinic. Requests to the API were made using the OkHTTP library. Data storage was done using Firebase Realtime Database (NoSQL) which provides fast operations and low latency.

​	Smart Planner app is a product that provides a complete user experience, and its development has successfully met all of its original objectives. The integration of modern technologies contributes to the quality of the application, and the diversity of functionalities and intuitive interface ensure easy and pleasant use.

____



[App demo on YouTube](https://youtu.be/BeGeU5YhScU)