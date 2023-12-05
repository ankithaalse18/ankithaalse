## **Roshni** : Assistant for blind

A specialized voice assistant designed to assist individuals with visual impairments is utilized for improving their quality of life. 

This system employs customized layouts and utilizes speech-to-text functionality, enabling access to crucial features tailored to their needs. 

Specifically, the system functions as a chat bot with dedicated features intended for the advancement of those with visual impairments.

## Fetaures which make "Roshni" unique:

The system comprises wearable headphones linked to a Logitech webcam connected to a Raspberry Pi.

The system interacts through speech input from the user and provides spoken responses.

Key Features:

1. **Description**:
  
    1. Roshni provides concise description of the user's surrounding.
    2. *Road Conditions*: Roshni gives the user an overview of the road conditions, which would further the visually impaired accordingly.
    3. Roshni also specifically mentions if the user is at common places like classrooms, kitchens, bedrooms, etc
    4. Responds the number of people, objects, etc in the frame of the webcam.

2. **Find**:

    1. Roshni resonds to commands like *find my purse?*, *check if my watch is in this room?* based on the presence of specified entities in the webcam's frame.
       
3. **Read**:

    1. Roshni also detects text from images and reads it loud.
    2. As a further application it can summarize articles from newspapers. 
    
4. **Fill forms**
    
    1. Roshni also reads out forms (majorly applicable for bank purposes)
    
5. **Mobile Interactions**

    1. It can read out notifications from mobile and as a further application respond to messages, emails, calender, etc
    
6. **Add ons**

    1. Roshni serves the basic features of a chat bot i.e. responds to question including time, lighting conditions, basic wh questions, etc.
    
    
Tech- stacks used:

    1. SpeechRecognizer, Google API for speech to text conversion
    
    2. Python Text to Speech https://pypi.org/project/pyttsx3/
    
    3. Object Recogniiton using *COCO Dataset*
    
    4. Google Cloud Vision API 
    
    5. Dialogflow
            
 Install Dependencies
 Download the credential for Google Vision API.
 Copy and paste the files at thr required position.
 
 ```
    git clone https://github.com/mansi1710/DobaraMatPuchana
    cd DobaraMatPuchana
    pip install -r requirements.txt
 ```
 
 Run Code:
 
 ```
 python main.py
 ```
