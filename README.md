# Dr_Receptionist
Final Year Capstone Project

Ever went to a hospital's reception and had difficulty booking appointments and getting your queries resolved? Long waiting lists and queues in hospitals make it difficult and a time consuming process. 
Presenting chatbot “Dr Receptionist”which aims to respond to customer by booking their appointment and send their questions/query to doctors over mail.
Now, Simple conversations between bot and patient can make the process of booking/cancelling appointments and asking queries so easy and effective .

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* Sign up into Google Dialogfow console using your google account.
* Create agent on Dialogflow console, name it accordingly
* What things you need to install the software and how to install them

### Installing

* Upload the intents code under the "intents" section of console.
* Upload entities code under "entities" section.
* In fulfillment, copy the index.js and package.json code from DialogflowFulfillment.zip->firebase->functions.
    * In fulfillment code of index.js, change email-id, password
    * Change and update user account details in order to connect to google calendar. You can get more information and watching https://youtu.be/4_MvIf_ULgc and follow the steps mentioned in the video.
  
### After successful deployment of code on firebase, check the working on the web demo by enabling "Web Demo" in Dialoagflow integrations.

You can add more integrations just by following the documentation mentioned in the console integrations page.

## Sample chatbot conversational flow(could be changed)

- User: Hi/hello/hey etc.
- Chatbot: “Hello! My name is Deep, and I am the virtual assistant of Doctor's reception. Would you
like to book/cancel an appointment or ask any question/queries with doctor?”.
- User: “mmmmmmmmmmm”……………
- Chatbot: “I could not understand what you said can you please repeat it?”
- User: “book an appointment”
- Chatbot: “So you would like to set an appointment”
- User: “Yes /Agreed/ No”
- Chatbot: “what date?”
- User: “19 September”
- Chatbot: “what time?”
- User: “10 AM”
- Chatbot: “I would like to confirm your appointment for 19 September at 10 AM. Please confirm?”
- User: “Yes/Sure”
- Chatbot: “Appointment set Successfully. Please visit on 19 September at 10 AM.”

### Features and functions to test

* Booking appointments and reflecting the appointments on Doctor's Google calendar
* Sending queries and get reply over email.

## Deployment

The chatbot has been deployed on the following platforms:
* Web Demo - https://bot.dialogflow.com/99245b5c-0c42-46b8-9efb-13f0bec00de4
* Dialogflow Phone Gateway - call on +1 408-785-3297
* Twilio - SMS texting on +14843242649
* Skype
* Facebook Messenger

## Built With

* [Google Dialogflow](http://www.console.dialogflow.com/) - The web framework and console used
* [Firebase and Google Cloud Platform](https://console.cloud.google.com) - Cloud Platform used 

## Contributing

For contributing, contact on deepak.dks1998@gmail.com. Can also call at 8802027419.

## Versioning

For the versions available, see the [tags on this repository].

## Authors

* **Deepak Sharma** - *Complete work* - E16CSE043, Bennett University, Greater Noida

## Policy

Privacy policy on website:- https://doctor-receptionist.flycricket.io/privacy.html
Privacy Policy on google docs:- https://docs.google.com/document/d/1DZ5e3mzIoqK0s4f37yfChVpQRpSB9L1Gjbkq51G5I0s/edit?usp=sharing

## Acknowledgments

* Priyanka Vergadia - https://github.com/priyankavergadia
* Inspiration by Dr. KK Biswas, Professor(CSE Department), Bennett University, Greater Noida
