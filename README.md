# Plantly Wiki
Welcome to Plantly an IoT Smart Garden, serverless cloud implementation and machine learning powered, go to our landing page https://pgp1.github.io to see what Planty is all about!

# General Setup

1) Navigate to arduino-microcontroller: https://github.com/PGP1/arduino-microcontroller. This repo contains the sourcecode for the sensor data collection of the garden. If you have an arduino, deploy our code, modify it to match your arduino sensor set up! 

- Deploy the code, and connect the arduino via Serial cable to a Raspberry Pi!

2) Navigate to rbpi-core: https://github.com/PGP1/rbpi-core. This is our Raspberry Pi source code, follow the instructions for installation and setup. 

3) Set up: https://github.com/PGP1/Dashboard, an example already has been deployed https://plantly.netlify.app/. This is our frontend.

4) Set up AWS Lambda Functions: https://github.com/PGP1/plantly-lambda-functions. This the inner mechanics of Plantly. We are a serverless application!

5) Set up Elastic Search: https://github.com/PGP1/elasticsearch. This helps us parse and process our data collected from our sensors!

6) Set up AI Model: https://github.com/PGP1/plantly-ai-model. The model that powers our smart notifications for smart gardening :)

