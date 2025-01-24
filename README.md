# Hyderabad / IOT Workshop
## Developing Applications on the Qualcomm Linux Platform 
A single day workshop for developers to build multimedia and AI applications.The goal is to create sample AI/ML or Multimedia applications using Qualcomm Linux platfom and capture feedback on your experience.

## Scope 
### Overview 
- If you have not done so, [set up your Qualcomm ID](https://myaccount.qualcomm.com/signup), confirm your email .This gives you access to the documentation and Qualcomm tools.
- Work on the task assigned to you.Please provide feedback as you navigate Qualcomm documentation in the excel sheet provided to you .
- Update the Feedback form (Excel) as you follow your workflow.Write down times you got lost, confused, or frustrated and, if applicable, how you resolved it.

## Introduction and Setup 
### Introduction  
- [Overview of the RB3 Gen2 Development Kit and its components]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-115/dev-kits.html?vproduct=1601111740013072&version=1.3 )
- Overview of the IQ-9100 Beta Evaluation Kit. (Contact Qualcomm staff for the preview document)

### What is in the Box  
- [Detailed explanation of the components in the Vision kit](https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-253/getting_started.html?vproduct=1601111740013072&version=1.3)  

### Setup and Configuration  
- Laptop setup:
- If using Windows Laptop follow instructions [here]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-253/set_up_the_device.html?vproduct=1601111740013072&version=1.3#panel-0-V2luZG93cw==).
- If using Ubuntu Laptop, following instructions [here]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-253/set_up_the_device.html?vproduct=1601111740013072&version=1.3#panel-0-VWJ1bnR1)
- If using a Macbook , follow steps [here]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-253/set_up_the_device.html?vproduct=1601111740013072&version=1.3#panel-0-bWFjT1M=)
  

## Build workflow:
#### Introduction to Qualcomm BUILD systems 
- [Overview of Qualcomm build system and user profiles]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-254/introduction.html?vproduct=1601111740013072&version=1.3)  

### Task 1.1: Download and build source code  for RB3Gen2 using QSC Launcher.
The goal is to download Qualcomm software using tools and build it and eventually program an existing RB3Gen2 with compiled software.
This task needs a Ubuntu workstation.
#### Reference 
- [QSC workflows]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-254/build_from_source_qsc_gui_intro.html?vproduct=1601111740013072&version=1.3)  
#### Testing and Feedback  
- Program the compiled build on RB3Gen2 and provide your feedback.

### Task 1.2: Download and build source code  for IQ8-Beta-EVK using QSC Launcher.
The goal is to downlod Qualcomm software using git and program an existing RB3Gen2 with the compiled software.
This task needs a Ubuntu workstation.
#### Reference
- [github flow for unregistered developer](https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-254/github_workflow_unregistered_users.html?vproduct=1601111740013072&version=1.3)  
#### Testing and Feedback  
- Program the compiled build on RB3Gen2 and provide your feedback

### Task 1.3: Download and build source code for IQ9 Chipset using QSC Launcher.
The goal is using an approved account of Qualcomm to download sources for the IQ9 Beta Development Kit. 
Qualcomm will provide credentials to use for download of the sources.
This task needs a Ubuntu workstation.
#### Reference 
- Follow steps from the pre-downloaded preview document provided to you by Qualcomm Staff 
#### Testing and Feedback  
- Program the BSP image on IQ-9100 Beta Evaluation Kit.

## AI Developer Workflow
Dedicated development utilizing the Multimedia and AI SDKs on the Qualcomm Linux platform.

### Setup and Configuration  
- To save time contact Qualcomm Staff to get the Platform ESDK.
- For Windows Laptop : Follow the steps [here](https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-41/getting-started.html?vproduct=1601111740013072&version=1.3) to enable a Ubuntu environment for your application development and copy the SDK to it.

### Task 2: Explore AI hub and integrate model from AI hub into existing Sample Applications.

The objective is to utilize existing models from the AI Hub for segmentation, detection, classification, and super resolution, and to execute the corresponding applications with these models.

#### References
- [Overview of AI Developer workflow]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-15B/ai-ml-developer-workflow.html?vproduct=1601111740013072&version=1.3)
  
#### Testing and Feedback 
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.


### Task 3: Bring new model to AI hub (BYOM) and integrate model into existing Sample Applications (supported models in IMSDK)
•	Try to get the latest open-source object detection model and utilize the AI Hub ‘Bring Your Own Model’ feature to convert and optimize it for Qualcomm SoCs. Integrate the optimized model into the application and execute it, as described in the previous step

#### References
- [Overview of AI Developer workflow]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-15B/ai-ml-developer-workflow.html?vproduct=1601111740013072&version=1.3)

#### Testing and Feedback 
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

### Task 4:  Setup QAIRT SDK, Compile & Optimize an AI model using SNPE. Integrate into existing Sample Application
- Download InceptionV3 or any other latest model, Convert and quantize the model using Qualcomm Neural Processing SDK to DLC and run the model using IMSDK based sample app.

#### References
- [Overview of AI Developer workflow]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-15B/ai-ml-developer-workflow.html?vproduct=1601111740013072&version=1.3)
- [Explore AI Sample applications](  https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-15B/ai-ml-reference-apps.html?vproduct=1601111740013072&version=1.3)

#### Testing and Feedback  

- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

### Task 5:   Setup QAIRT SDK, Compile & Optimize an AI model using QNN.  Integrate into existing Sample Application
-  Download InceptionV3 or any other latest model, Convert and quantize the model using Qualcomm AI Engine Direct SDK to BIN and run the model using IMSDK based sample app

#### References
- [Overview of AI Developer workflow]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-15B/ai-ml-developer-workflow.html?vproduct=1601111740013072&version=1.3)
- [Explore AI Sample applications](  https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-15B/ai-ml-reference-apps.html?vproduct=1601111740013072&version=1.3)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

## QIM SDK Sample App
### Task 6: Develop your first QIM SDK application

#### Introduction to QIM SDK  
- [Overview of QIM SDK](https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-50/overview.html?vproduct=1601111740013072&version=1.3&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)  
- [Overview of Application development]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-51/introduction.html?vproduct=1601111740013072&version=1.3&facet=Qualcomm%20Intelligent%20Multimedia%20Product%20(QIMP)%20SDK )  

#### Hands on Development  

- [Develop a Simple multimedia application]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-51/application-development.html?vproduct=1601111740013072&version=1.3&facet=Qualcomm%20Intelligent%20Multimedia%20Product%20(QIMP)%20SDK)  

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

### Task 7: Develop New Reference application .
#### Introduction to QIM SDK
Thae goal is to use existing refernee applications as reference to create a new application.

- [Overview of QIM SDK](https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-50/overview.html?vproduct=1601111740013072&version=1.3&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)  

#### Hands on Development  
- [Customize Sample applications]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-51/customize-sample-applications.html?vproduct=1601111740013072&version=1.3&facet=Qualcomm%20Intelligent%20Multimedia%20Product%20(QIMP)%20SDK)
  
#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.



#### Introduction to QIM SDK
- [Overview of QIM SDK]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-50/overview.html?vproduct=1601111740013072&version=1.3&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)  
- [Python Sample applications]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-50/python-sample-applications.html?vproduct=1601111740013072&version=1.3&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)   

#### Hands on Development  
- Run the prebuilt python application.
- Customize and run python samples.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

## Python App Development
### Task 8:  Develop Application with Python API of GStreamer
#### Introduction to QIM SDK  
- [Overview of QIM SDK]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-50/overview.html?vproduct=1601111740013072&version=1.3&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)  
- [Python samples]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70017-50/python-sample-applications.html?vproduct=1601111740013072&version=1.3&facet=Qualcomm%20Intelligent%20Multimedia%20SDK) 

#### Hands on Development  
- Use on target of host based development and push the file through adb and verify.  

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback.

## Explore Sample and Experience application.
The goal is to setup the Qualcomm Reference hardware provided and explore capabilities of hardware by running the sample applications.
### Task 9: Explore existing sample application on RB3Gen2 (GST Sample application and Python sample application )

- [Exploration Experience application ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-253/demo_app.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f) 

- [Explore AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-50/example-applications.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.

## MM Tasks
### Task 10.1: Video encode with GMSL/MIPI Camera using Gstreamer commands
The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to achieve the task (Encoding video with data from camera stream).
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.

### Task 10.2: Audio Decode and encode using Gstreamer application.
The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to load the required pre requisites and do audio encode and decode at GST level.
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.
- 
### Task 10.3: Verify driver level playback and record.
The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to load the required pre requisites and do audio encode and decode at platform/HAL level.
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.
 
### Task 11.1: Video Playback using GST command
The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to perform video playback using GST commands.
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.

### Task 11.2: Offline video decode using v4l2 test app
The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to perform  offline decode using v4l2 apps.
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.


### Task 12: Implement OpenCV Rotate application with fastCV
The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to perform  install pre-requisites needed to crete or compile any application like the 
rotate application using fastCV.
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback
- 
### Task 13.1: Weston EGL Client commands
The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to test EGL client of Weston .
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback
- 
### Task 13.2: DRM Mode test
The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to perform DRM mode test.
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback

### Task 13.3: Compile and run GLES and Vulcan applications.
The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to perform GLES and Vulkan sample application.
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback
