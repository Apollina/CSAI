# CSAI
Hack for the [HackJunction2018](https://hackjunction.com/) 

Project [description](https://projects.hackjunction.com/projects/junction-2018/5bf85dae6a75040015931cc8)

![alt text](https://github.com/ziky90/CSAI/blob/master/images/demo.png)

## Technical description of all the components of the system

We have build a system that consist of one frontend application and 2 separate backend appliacations.

### Frontend Application
https://github.com/Apollina/FAEMDE

Vue.js based fromntend application that enables and agregates:
- On the fly customer video face tracking and video analysis
- On the fly chat sentiment analysis
- Aggregation of all the algorithms to the dashboard and the leaderboard

### Computer Vision related backend
https://github.com/ziky90/FAEMDE_python_backend

Python Flask server based aplication for:
- Face localization: Using Viola-Jones algoritm
- Facial Expression detection: Using the pretrained CNN model from the EmoPy library

### NLP and database related backend
https://github.com/Ihsara/TEEMDE

Python Flask server and SQL databse based application that enables:
- Sending messages
- Perform messages sentiment analysis using the TextBlob NLP library.
