# Event-Management-App
An event management application made with Java and JavaFx

MakeMyEventSpecial is a hotel(event) booking application that features three main categories:
wedding, party and birthday. 
When a user selects a category, they are presented with a list of hotels that are popular for that type
of event.Clicking on a hotel provides detailed information about it. The application uses FireStore for handling Login and sign-up processes and Twilio API for sending confirmation message.

I have provided the code but here you have to enter personal details to run the code.
First in FireStore you have to put the private key(.json file) in resourses and give its address in the code.
To get the private key, follow these steps:
- Go to FireBase console and signup
- Create a project and give the appropriate name
- Now click on settings icon and inside project setting, there is option of Service accounts
- Select 'java' and generate key
- put that downloaded private key in resources folder

Second for Twilio API, you need four things:
1) Twilio Phone Number - you will get that when you register for Twilio
2) Account SID - present in Account Info
3) Auth Token - present in Account Info
4) Service SID - go to Dashbord -> Verify -> Services

Note: You can only send confirmation message to verified numbers only. So you need to add verified numbers to send message.


Team Members:
1) Prathamesh Suyog Dhadankar
2) Prajwal Pravin Desai
3) Parth Pritam Patil
4) Onkar Vikas Pawar

Thats all,
Thank you!