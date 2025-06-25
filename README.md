# GYM-MASTER 🏋️‍♂️

A cutting-edge fitness application that combines AI coaching, real-time form correction, and social competition to transform your workout experience.

# How to Run
- Head over to the [Frontend](https://huggingface.co/spaces/Jguan10/GymMasterFront)
- Start up the [Backend](https://huggingface.co/spaces/Jguan10/GymMasterBack)
- Start up the [Flask API](https://huggingface.co/spaces/Jguan10/GymMasterAPI)
- Then start doing push-ups!

AI Coach could not be deployed, but feel free to test out the push-up model!

# What does it do?

GymMaster is a computer vision model trained to recognize and count your pushups. It's also fitted with an AI coach and cheerleader to complete all your at home workout needs!

# How does it work?
- We utilized mediapipe to build a push-up model trained on our data!
- The model calculates angles between certain nodes, like your shoulder and arms, to count your push-up reps
![image](https://github.com/user-attachments/assets/2bfd3a9a-8045-431d-87f4-fe5377fad1dd)
- AI Coach takes in your body's positional data and determines points of improvement based on ideal form and position
- AI Cheerleader steps in every few reps to generate words of encouragement

# Tech Stack
- NodeJS
- ReactJS
- MongoDB
- MediaPipe
- LangChain
- Flask
- Docker
  
