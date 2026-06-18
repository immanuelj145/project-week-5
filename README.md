# project-week-5
### How To Run This Program
1. Download or clone this repo to your machine
2. Navigate to the repo in your terminal
3. Now, run the following command: javac *.java
4. Next, this command: java FlexibleNotificationSystem.java
5. The program will print messages in your terminal

### Requirements to Run This Program
1. Java RunTime
2. Windows, MacOS, or Linux

### Components of This Program
1. FlexibleNotificationSystem: main class that instantiates/calls all classes
2. AlertSystem: sets the Medium, sends the message, logs the message
3. NotificationMedium: interface that defines the send() method
4. SMSService — implements the NotificationMedium to send text notifications
5. WhatsAppService — implements the NotificationMedium to send WA notifications
6. EmailService: implements the NotificationMedium to send email notifications

### Example Output
Starting Alert System

[EmailService] Sending Email: Email notification example 1 
[EmailService] Sending Email: Email notification example 2

Switching Notification Medium 
[SMSService] Sending SMS: SMS notification example 1 
[SMSService] Sending SMS: SMS notification example 2

[WhatsApp] Sending WhatsApp: WhatsApp notification example 1 
[WhatsApp] Sending WhatsApp: WhatsApp notification example 2

Session Message Log

Email notification example 1
Email notification example 2
SMS notification example 1
SMS notification example 2
WhatsApp notification example 1
WhatsApp notification example 2
