# Hyderabad / IOT Workshop
## Developing Applications on the Qualcomm Linux Platform 
A single day workshop for developers to build multimedia and AI applications .The goal is to create sample AI/ML or Multimedia applications using Qualcomm Linux platfom and capture feedback on development experience.

## Scope 
### Overview 
- If you have not done so, [set up your Qualcomm ID](https://myaccount.qualcomm.com/signup), confirm your email, then [sign the PKLA](https://qualcomm.com/agreements) using your Qualcomm ID.  This gives you access to the documentation. 

- Work on the task that is assigned to you by Nitin. Please provide feedback as you navigate Qualcomm documentation in the excel sheet provided to you by Nitin.
  
-  Update the Feedback Forum as you follow your workflow.Write down the any time you are lost, confused, or frustrated and, if applicable, how you resolved it.

## Introduction and Setup 
### Introduction  
- [Overview of the RB3 Gen2 Development Kit and its components]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-115/dev-kits.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)  

### What is in the Box  
- [Detailed explanation of the components in the Vision kit](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-253/getting_started.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)  

### Setup and Configuration  
- Laptop setup:
- If using Windows Laptop follow instructions [here](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-253/set_up_the_device.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f#panel-0-0-1).
- If using Ubuntu Laptop, following instructions [here](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-253/set_up_the_device.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f#set-up-the-ubuntu-host)
- If using a Mac , follow steps [here](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-253/set_up_the_device.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f#panel-0-0-2)
  

## Build procedures:
#### Introduction to Qualcomm BUILD systems 

- [Overview of Qualcomm build system and user profiles](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-254/introduction.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)  

### Task 1: Download and build source code of RB3Gen2 using GUI tools
The goal is to download Qualcomm software using tools and build it and eventually program an existing RB3Gen2 with compiled software.
This task needs a Ubuntu workstation.
#### Reference 
- [QSC workflows](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-254/build_from_source_qsc_gui_intro.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)  
#### Testing and Feedback  
- Program the compiled build on RB3Gen2 and provide your feedback.

### Task 2: Download and build source code of RB3Gen2 using git commands
The goal is to downlod Qualcomm software using git and program an existing RB3Gen2 with the compiled software.
This task needs a Ubuntu workstation.
#### Reference
- [github flow for unregistered developer](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-254/github_workflow_unregistered_users.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)  
#### Testing and Feedback  
- Program the compiled build on RB3Gen2 and provide your feedback

### Task 3: Develop and build source code of IQ9 Beta Development kit.
The goal is using an approved account of Qualcomm to download sources for the IQ9 Beta Development Kit. 
Qualcomm will provide credentials to use for download of the sources.
This task needs a Ubuntu workstation.
#### Reference 
- [github flow for registered developer](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-254/build_from_source_github_intro.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)  
#### Testing and Feedback  
- Test the application on the IQ9 Beta Development Kit.

## Focused AI/ML Development 
Dedicated development utilizing the Multimedia and AI SDKs on the Qualcomm Linux platform

### Task 4: Compile and optimize an AI model using SNPE
- Download InceptionV3 or any other latest model, Convert and quantize the model using Qualcomm Neural Processing SDK to DLC and run the model using IMSDK based sample app.
  
#### References
- [Overview of AI Developer workflow]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-15B/aiml-developer-workflow.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)  
- [Exploration of the AI sample applications](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-50/ai-ml-sample-applications.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

### Task 5: Develop Face Detection application
- The goal is to use an face detection model (provided by Qualcomm) and write or modify an existing application to run face detection on camera stream.

#### References
- [Overview of AI Developer workflow]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-15B/aiml-developer-workflow.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)
- [Object detection Sample app](https://git.codelinaro.org/clo/le/platform/vendor/qcom-opensource/gst-plugins-qti-oss/-/blob/imsdk.lnx.2.0.0.r2-rel/gst-sample-apps/gst-ai-object-detection/main.c?ref_type=heads)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

### Task 6:  Integrate Custom Model in an Application
- The objective is to utilize existing models from the AI Hub for segmentation, detection, classification, and super resolution, and to execute the corresponding applications with these models.
- Try to get the latest open-source object detection model and utilize the AI Hub ‘Bring Your Own Model’ feature to convert and optimize it for Qualcomm SoCs. Integrate the optimized model into the application and execute it, as described in the previous step

#### References
- [Overview of AI Developer workflow]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-15B/aiml-developer-workflow.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)

#### Testing and Feedback  

- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

## Focused Multimedia and Python Development 
### Task 7: Develop your first QIM SDK application

#### Introduction to QIM SDK  
- [Overview of QIM SDK]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-50/overview.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)  
- [Overview of Application development]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-51/introduction.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20Product%20(QIMP)%20SDK)  

#### Hands on Development  

- [Develop a Simple multimedia application](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-51/application-development.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20Product%20(QIMP)%20SDK)  

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

### Task 8: Develop Python Application 
#### Introduction to QIM SDK
- [Overview of QIM SDK]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-50/overview.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)  
- [Python Sample applications](TBD)   

#### Hands on Development  
- Run the prebuilt python application.
- Customize and run python samples.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

## Explore Sample and Experience application.
The goal is to setup the Qualcomm Reference hardware provided and the  Host PC and explore the capablities of the hardware .
### Task 9: Explore existing sample application on RB3Gen2.

- [Exploration of the Experience application ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-253/demo_app.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f) 

- [Explore of the AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-50/example-applications.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback .
  
### Task 10: Explore existing sample application on IQ9 Beta DevKit

- [Exploration of the Experience application ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-253/demo_app.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f) 

- [Explore of the AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-50/example-applications.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback .
