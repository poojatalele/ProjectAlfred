# ProjectAlfred

# PROJECT ALFRED

Technical Requirements Document (TRD) for Alfred the Humanoid Robot

Project Overview

## 1. Introduction

This document outlines the technical requirements for Alfred, a humanoid robot designed to greet and interact with visitors at the Innovation Lab of Scaler School of Technology. Alfred's primary purpose is to enhance the visitor experience by providing a warm welcome and engaging in conversations.

## 2. Scope

The project covers the design and development of a humanoid robot capable of detecting, tracking, and interacting with guests through voice and limited physical gestures.

## 3. System Overview

The system comprises the following main components:

  - **Computer Vision System**: Responsible for detecting and tracking visitors within the reception area.
  - **Speech Recognition System**: Enables Alfred to understand and interpret spoken commands and queries from visitors.
  - **Natural Language Processing (NLP) System**: Processes and interprets the recognized speech to generate appropriate responses.
  - **Text-to-Speech System**: Converts the generated responses into audible speech for communication with visitors.
  - **Robotic Control System**: Controls the movement and gestures of Alfred's body parts (head, arms, and hands) to exhibit expressive body language.

## 4. Objectives & Key Results (OKRs)

  - **Engagement with Guests**: Track and engage every guest entering the lab.
  - **Metric**: Number of guests greeted, average conversation duration.

  - **Guest Satisfaction**: Achieve high levels of satisfaction through interactive features.
  - **Metric**: Positive feedback percentage, average guest rating.


## 5. Functional Requirements

### 5.1. Visitor Detection and Tracking
  - Detect when a visitor enters the reception area using computer vision techniques.
  - Track the visitor's movement within the reception area until they exit.

### 5.2. Speech Recognition and Natural Language Understanding
  - Recognize and interpret spoken commands and queries from visitors using speech recognition and NLP systems.
  - Understand and respond to greetings, introductions, and general conversational queries.
  - Comprehend and respond to specific commands and questions related to scheduling meetings, checking availability, and providing information about Scaler School     of Technology and the Innovation Lab.

### 5.3. Conversation and Response Generation
  - Engage in natural and contextual conversations with visitors.
  - Generate appropriate responses based on the visitor's input and the conversation flow.
  - Incorporate expressive body language and gestures (e.g., waving, nodding) during conversations.

### 5.4. Notification System
  - Notify the relevant personnel or group via WhatsApp when a visitor arrives to meet them.

### 5.5. User Experience
  - Provide a warm and welcoming experience for visitors.
  - Create an "Aha!" moment by showcasing the advanced capabilities of a humanoid robot.
  - Engage visitors with interesting facts and information about Scaler School of Technology and the Innovation Lab.

## 6. Non-Functional Requirements

### 6.1. Performance
  - The system should respond to visitor interactions in real-time, with minimal delays(i.e the response time must be less than 2 seconds for conversation         initiations and commands)
  - The speech recognition and natural language processing should be accurate and reliable.
    
### 6.2. Scalability
  - The system should be designed to handle multiple simultaneous visitors without significant performance degradation.
  -  Design should allow for future upgrades, including more advanced AI capabilities and physical movements.
    
### 6.3. Security
  - The system should have appropriate security measures in place to protect against unauthorized access or misuse.

### 6.4. Reliability
  - System should operate continuously without failure during business hours.

### 6.5. Usability
  - The system should be intuitive and user-friendly, requiring minimal instructions or guidance for visitors to interact with Alfred.

## 7. System Architecture

- ### Hardware:
  - Core processing unit capable of handling AI computations.
  - Sensors for motion detection and visitor tracking.
  - Cameras and microphones for visual and audio inputs.
  - Actuators for head and hand movements.
- ### Software:
  - Vision processing using OpenCV, Tensorflow, PyTorch.
  - Natural Language Processing and generation through LLMs.
  - Integration of Speech-to-Text and Text-to-Speech technologies.
  - Real-time communication tools for notifications.

## 8. Target Audience

  - **Primary Audience**: Visitors including parents, super mentors, and leaders.
  - **Secondary Audience**: None specified.

## 9. Known Issues & Limitations

  - **Mobility**: Alfred will be stationary, lacking leg movements.
  - **Speech Recognition**: Potential inaccuracies due to ambient noise and speech complexities.

## 10. Development and Testing

 ### 10.1. Development

  - Hardware assembly and basic motion capability setup.
  - Integration of visual and auditory recognition systems.
  - Implementation of AI for interaction and responsiveness.
  - Iterative development approach with regular testing and validation.
  - Iterative feedback incorporation.

### 10.2. Testing

  - Functional Testing: Verify all interactive capabilities as per requirements.
  - Performance Testing: Ensure responsiveness and handling capacity under varying loads.
  - Usability Testing: Conduct trials with real users to assess experience and satisfaction.


## 11. Technical Constraints

### 11.1. Hardware Limitations
  - Alfred will not have leg movements in the initial version (v0).
  - The quality of audio input may be limited, affecting the speech recognition capabilities.

### 11.2. Software Dependencies
  - The system will rely on various software libraries and frameworks for computer vision, speech recognition, natural language processing, and robotic control.

## 12. Future Enhancements
  - Incorporate advanced natural language processing capabilities to enable more complex and contextual conversations.
  - Integrate with other systems or services within Scaler School of Technology for enhanced functionality (e.g., scheduling, resource management).
  - Explore the possibility of adding additional sensors or components to enhance Alfred's capabilities (e.g., facial recognition, emotion detection).

