# Hyderabad / IOT Workshop

## Developing Applications on the Qualcomm Linux Platform 
A single day workshop for developers to build multimedia and AI applications. The goal is to Explore application development using Explore sample apps using QDemo and run sample AI/ML or Multimedia applications using Qualcomm Linux platform and capture feedback on the experience.

## Scope 
### Overview 
- If you have not done so, [set up your Qualcomm ID]( https://myaccount.qualcomm.com/signup), confirm your email .This gives you access to the documentation and Qualcomm tools.
- Work on the task assigned to you. Please provide feedback as you navigate Qualcomm documentation in the excel sheet provided to you .
- Update the Feedback form (Excel) as you follow your workflow. Write down times you got lost, confused, or frustrated and, if applicable, how you resolved it.

## Introduction and Setup 
### Introduction  
Links to important hardware and software tools to be used for the workshop.
- [Overview of the RB3 Gen2 Development Kit and its components]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-115/dev-kits.html?vproduct=1601111740013072&version=1.5 )
- [Overview of the IQ9 Beta Evaluation Kit]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-115/dev-kits.html?vproduct=1601111740013072&version=1.5 )
- [Qualcomm VSCode IDE]( https://docs.qualcomm.com/bundle/publicresource/topics/80-79972-1/overview.html )
- [Qualcomm Device Cloud]( https://qdc.qualcomm.com/ )

### What is in the Box  
- [Detailed explanation of the components in the Vision kit]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-253/rb3-qsg-whats-in-box.html#what-is-included)

### Setup and Configuration  
- Laptop setup:
- If using Windows Laptop follow instructions [here]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-251/upgrade-rb3gen2-software.html#panel-0-V2luZG93cw==).
- If using Ubuntu Laptop, following instructions [here]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-251/upgrade-rb3gen2-software.html#panel-0-VWJ1bnR1)
- If using a Macbook , follow steps [here](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-251/upgrade-rb3gen2-software.html#panel-0-bWFjT1M=)
  

## Build workflow:
#### Introduction to Qualcomm BUILD systems 
- [Overview of Qualcomm build system and user profiles]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-254/introduction.html?vproduct=1601111740013072&version=1.5)  

## AI Developer Workflow
Dedicated development utilizing the Multimedia and AI SDKs on the Qualcomm Linux platform.

### Task 1: Explore AI hub and integrate model from AI hub into existing Sample Application.

The objective is to utilize existing models from the AI Hub for segmentation, detection, classification, and super resolution, and to execute the corresponding applications with these models.

#### References
- [Overview of AI Developer workflow]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-15B/introduction.html?vproduct=1601111740013072&version=1.5)
  
#### Testing and Feedback 
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

### Task 2: Bring new model to AI hub (BYOM) and integrate model into existing Sample Applications (supported models in IMSDK)

Try to get the latest open-source object detection model and utilize the AI Hub ‘Bring Your Own Model’ feature to convert and optimize it for Qualcomm SoCs. Integrate the optimized model into the application and execute it, as described in the previous step.

#### References
- [Overview of AI Developer workflow]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-15B/introduction.html?vproduct=1601111740013072&version=1.5)
- [Integrate AIHUB Models](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-15B/develop-your-own-application-im-sdk.html?vproduct=1601111740013072&version=1.5)
  
#### Testing and Feedback 
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.


### Task 3: Setup QAIRT SDK, Compile & Optimize an AI model using SNPE/QNN Integrate into existing Sample Application

- Download InceptionV3 or any other latest model, Convert and quantize the model using Qualcomm Neural Processing SDK to DLC and run the model using IMSDK based sample app.
- Download InceptionV3 or any other latest model, Convert and quantize the model using Qualcomm AI Engine Direct SDK to BIN and run the model using IMSDK based sample app

#### References
- [Overview of AI Developer workflow]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-15B/introduction.html?vproduct=1601111740013072&version=1.5)
- [Explore AI Sample applications]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-15B/ai-ml-reference-apps.html?vproduct=1601111740013072&version=1.5)

#### Testing and Feedback  

- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.


### Task 4: Experience HW Benchmarking Sample APP and SNPE Python container

-   Follow the IMSDK documentation to execute supported reference sample applications on RB3Gen2 device.

#### References
- [HW Benchmarking App](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/vision_ai_demo_app.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)
- [SNPE Python container]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/image-segmentation-using-python.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.


## QIM SDK Sample App:
### Task 5: Develop your first QIM SDK application

#### Introduction to QIM SDK  
- [Overview of QIM SDK]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/example-applications.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)  
- [Overview of Application development](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-51/application-development.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)  

#### Hands on Development  

- [Develop a Simple multimedia application]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-51/content-develop-your-first-application.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20Product%20(QIMP)%20SDK#content-develop-your-first-application)  

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.


### Task 6: Develop new Reference Application – GST based

#### Introduction to QIM SDK
Thae goal is to use existing reference applications as reference to create a new application.

- [Overview of QIM SDK]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/example-applications.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)
- [Customize Sample applications]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-51/customize-sample-applications.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20Product%20(QIMP)%20SDK)

#### Hands on Development  
- Run the prebuilt python application.
- Customize and run python samples.
  
#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.


### Task 7: Experience One-click launcher and execute sample application from One Click launcher

- [Experience application using One Click launcher]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-253/run-sample-apps-qdemo.html)
- [Explore AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/example-applications.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.


### Task 8: Create IMSDK Container Image and execute the sample applications inside the container

- [IMSDK Docker Doc](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/application-deployment-within-container-api-gstd.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK) 

#### Testing and Feedback  
- Test the sample application on the RB3 Gen2 and provide your feedback.


## Python App Development
### Task 9: Develop Application with Python API of Gstreamer

#### Introduction to QIM SDK  
- [Overview of QIM SDK]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/example-applications.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)  
- [Python samples]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/python-sample-applications.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK) 

#### Hands on Development  
- Use on target of host based development and push the file through adb and verify.  

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback.


## Run All Sample Apps
### Task 10: Explore existing sample Applications on RB3Gen2 – GST Sample Applications, and Python Sample Applications

- [Exploration Experience application ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-253/run-sample-apps-qdemo.html  ) 

- [Explore AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/example-applications.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.


## IDE Documentation
### Task 11: Experience the IDE and Execute the sample applications inside the IDE

- [Exploration Sample apps using IDE]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-51/content-develop-your-first-application.html#develop-using-qualcomm-visual-studio-code-extension) 
- [Explore AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/example-applications.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the IDE on the RB3 Gen2 and provide your feedback.


## MM Tasks
### Task 12.1: Video encode with GMSL/MIPI Camera using Gstreamer commands

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to achieve the task (Encoding video with data from camera stream).
No documentation reference provided.Expect engineer to navigate to findout the instructions.

Note:
#### For RB3Gen2 (QCS6490): <br>
#### GMSL camera : <br>
Supported. Please check GMSL camera is connected to RB3 device .<br>
#### MIPI camera:<br>
Supported. Camera sensors are attached to device by default.<br>
#### USB camera:<br>
Supported. Please check USB camera connected on RB3 device.<br>
 
 
#### For IQ9-EVK (QCS9075) please check:<br>
#### GMSL camera :<br>
Supported. IQ9-EVK core kits don’t have GMSL interface by default. <br>
We need to connect GMSL board on top of it to connect GMSL cameras..<br>
please check GMSL board and GMSL camera  that are connected on top core kit..<br>
#### MIPI camera :<br>
Supported. Please check MIPI camera connected on IQ9-EVK core kit.<br>
#### USB camera:<br>
Supported. Please check USB camera connected on IQ9-EVK core kit.<br>
 
#### For IQ8-Beta EVK (QCS8300) please check:<br>
#### GMSL camera :<br>
Supported. Please check GMSL camera is connected to device<br>
#### MIPI camera:<br>
Not supported<br>
#### Usb camera:<br>
Supported. Please check USB camera connected on Ride SX device<br>

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.


### Task 12.2: Audio decode and encode using GStreamer application (RB3Gen2)

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to load the required pre requisites and do audio encode and decode at GST level.
#### Reference
https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/gst-audio-video-encode.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK 

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.


### Task 12.3: Verify driver level playback and record

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to load the required pre requisites and do audio encode and decode at platform/HAL level.
#### References
- [Qualcomm Linux Audio Guide - Addendum]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-16A/audio-addendum.html?vproduct=1601111740013072&version=1.5&facet=Audio)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.


## Video Task
### Task 13.1: Video playback using GST command

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to perform video playback using GST commands.
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.


### Task 13.2: Offline Video decode using V4l2 test app (Host PC Kernel >v6.6)

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to perform  offline decode using v4l2 apps.
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.


### Task 14: Implement OpenCV rotate application with FastCV

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to perform  install pre-requisites needed to crete or compile any application like the 
rotate application using fastCV.
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback

### Task 15: Graphics Task
#### Task 15.1: Weston EGL client application commands

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to test EGL client of Weston .
No documentation reference provided. Expect engineer to  navigate to find out the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback


### Task 15.2: Compile and run GLES and Vulkan applications.

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to perform GLES and Vulkan sample application.
No documentation reference provided. Expect engineer to  navigate to find out the instructions.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback


## Upgrade Workflow
### Task 16:Upgrade existing RB3Gen2
- Upgrade RB3Gen2 with older software to latest version 
- Use documentation to find out commands to find QLI  version on hardware.
- Perform upgrade following documents.
- Find out hardware variant ( core or vision kit ) 
- Program CDT based on hw variant at hand .
- Confirm basic apps work .

Check time to complete, check if instructions are clear and confirm flashing worked as documented.
<br>
<br>
<br>
<br>
