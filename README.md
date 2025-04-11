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
- [Overview of the RB3 Gen2 Development Kit and its components]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-115/dev-kits.html?vproduct=1601111740013072&version=1.4 )
- Overview of the IQ-9100 Beta Evaluation Kit. (Contact Qualcomm staff for the preview document)

### What is in the Box  
- [Detailed explanation of the components in the Vision kit](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-253/qsg-landing-page.html)

### Setup and Configuration  
- Laptop setup:
- If using Windows Laptop follow instructions [here]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-253/upgrade-rb3gen2-software.html#panel-0-V2luZG93cw==).
- If using Ubuntu Laptop, following instructions [here]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-253/upgrade-rb3gen2-software.html#panel-0-VWJ1bnR1)
- If using a Macbook , follow steps [here]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-253/upgrade-rb3gen2-software.html#panel-0-bWFjT1M=)
  

## Build workflow:
#### Introduction to Qualcomm BUILD systems 
- [Overview of Qualcomm build system and user profiles]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-254/introduction.html?vproduct=1601111740013072&version=1.4)  

### Task 1.1: Download and build source code  for RB3Gen2 using QSC Launcher.
The goal is to download Qualcomm software using tools and build it and eventually program an existing RB3Gen2 with compiled software.
This task needs a Ubuntu workstation.
#### Reference 
- [QSC workflows]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-254/build_from_source_qsc_gui_intro.html?vproduct=1601111740013072&version=1.4)  
#### Testing and Feedback  
- Program the compiled build on RB3Gen2 and provide your feedback.

### Task 1.2: Download and build source code  for IQ8-Beta-EVK using QSC Launcher.
The goal is to downlod Qualcomm software using QSC too and program an IQ8-Beta-EVK with the compiled software.
This task needs a Ubuntu workstation.
#### Reference
 - [QSC workflows]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-254/build_from_source_qsc_gui_intro.html?vproduct=1601111740013072&version=1.4)   
#### Testing and Feedback  
- Program the compiled build on IQ8-Beta-EVK and provide your feedback

### Task 1.3: Download and build source code for IQ9 Chipset using QSC Launcher.
The goal is to downlod Qualcomm software using QSC too and program an IQ9-Beta-EVK with the compiled software.
This task needs a Ubuntu workstation.
#### Reference 
 - [QSC workflows]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-254/build_from_source_qsc_gui_intro.html?vproduct=1601111740013072&version=1.4)   
#### Testing and Feedback  
- Program the BSP image on IQ-9100 Beta Evaluation Kit.

## AI Developer Workflow
Dedicated development utilizing the Multimedia and AI SDKs on the Qualcomm Linux platform.

### Setup and Configuration  
- To save time contact Qualcomm Staff to get the Platform ESDK.
- For Windows Laptop : Follow the steps [here](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-41/set-up-windows-subsystem-for-linux-on-windows-11.html?vproduct=1601111740013072&version=1.4) to enable a Ubuntu environment for your application development and copy the ESDK to it.

### Task 2: Explore AI hub and integrate model from AI hub into existing Sample Applications.

The objective is to utilize existing models from the AI Hub for segmentation, detection, classification, and super resolution, and to execute the corresponding applications with these models.

#### References
- [Overview of AI Developer workflow](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-15B/introduction.html?vproduct=1601111740013072&version=1.4)
- [Integrate AIHUB Models](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-15B/develop-your-own-application-im-sdk.html?vproduct=1601111740013072&version=1.4)
  
#### Testing and Feedback 
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.


### Task 3: Bring new model to AI hub (BYOM) and integrate model into existing Sample Applications (supported models in IMSDK)
•	Try to get the latest open-source object detection model and utilize the AI Hub ‘Bring Your Own Model’ feature to convert and optimize it for Qualcomm SoCs. Integrate the optimized model into the application and execute it, as described in the previous step

#### References
- [Overview of AI Developer workflow](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-15B/introduction.html?vproduct=1601111740013072&version=1.4)

#### Testing and Feedback 
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

### Task 4: Setup QAIRT SDK, Compile & Optimize an AI model using SNPE/QNN. Integrate into existing Sample Application
- Download InceptionV3 or any other latest model, Convert and quantize the model using Qualcomm Neural Processing SDK to DLC and run the model using IMSDK based sample app.
- Download InceptionV3 or any other latest model, Convert and quantize the model using Qualcomm AI Engine Direct SDK to BIN and run the model using IMSDK based sample app

#### References
- [Overview of AI Developer workflow](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-15B/introduction.html?vproduct=1601111740013072&version=1.4)
- [Explore AI Sample applications](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-15B/ai-ml-reference-apps.html?vproduct=1601111740013072&version=1.4)

#### Testing and Feedback  

- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

### Task 5: Experience Qualcomm Developers Cloud(QDC) Workflow in AI developer workflow and execute sample application
-   Follow the QDC documentation to execute supported reference sample applications on RB3Gen2 device on cloud. 

#### References
- [Overview of AI Developer workflow](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-15B/introduction.html?vproduct=1601111740013072&version=1.4)
- [Explore QDC Documentation](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-15B/sample-app-qdc.html?vproduct=1601111740013072&version=1.4)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

## QIM SDK Sample App
### Task 6: Develop your first QIM SDK application

#### Introduction to QIM SDK  
- [Overview of QIM SDK](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-50/example-applications.html?vproduct=1601111740013072&version=1.4&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)  
- [Overview of Application development](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-51/introduction.html?vproduct=1601111740013072&version=1.4&facet=Qualcomm%20Intelligent%20Multimedia%20Product%20(QIMP)%20SDK)  

#### Hands on Development  

- [Develop a Simple multimedia application](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-51/content-develop-your-first-application.html?vproduct=1601111740013072&version=1.4&facet=Qualcomm%20Intelligent%20Multimedia%20Product%20(QIMP)%20SDK#content-develop-your-first-application)  

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

### Task 7: Develop New Reference application .
#### Introduction to QIM SDK
Thae goal is to use existing reference applications as reference to create a new application.

- [Overview of QIM SDK](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-50/example-applications.html?vproduct=1601111740013072&version=1.4&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)
- [Customize Sample applications](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-51/customize-sample-applications.html?vproduct=1601111740013072&version=1.4&facet=Qualcomm%20Intelligent%20Multimedia%20Product%20(QIMP)%20SDK)

#### Hands on Development  
- Run the prebuilt python application.
- Customize and run python samples.
  
#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

## Python App Development
### Task 8:  Develop Application with Python API of GStreamer
#### Introduction to QIM SDK  
- [Overview of QIM SDK](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-50/example-applications.html?vproduct=1601111740013072&version=1.4&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)  
- [Python samples](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-50/python-sample-applications.html?vproduct=1601111740013072&version=1.4&facet=Qualcomm%20Intelligent%20Multimedia%20SDK) 

#### Hands on Development  
- Use on target of host based development and push the file through adb and verify.  

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback.

## Explore Sample and Experience application.
The goal is to setup the Qualcomm Reference hardware provided and explore capabilities of hardware by running the sample applications.
### Task 9: Explore existing sample application on RB3Gen2 (GST Sample application and Python sample application )

- [Exploration Experience application ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-253/demo_app.html) 

- [Explore AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-50/example-applications.html?vproduct=1601111740013072&version=1.4&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.

### Task 10: Experience One-click launcher and execute sample application from One Click launcher

- [Experience application using One Click launcher](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-253/demo_app.html)
- [Explore AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-50/example-applications.html?vproduct=1601111740013072&version=1.4&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.

### Task 11: Experience Gstreamer command line use cases and try building new use cases.

- [Gstreamer CLI Use cases](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-50/gstreamer-application-use-cases.html?vproduct=1601111740013072&version=1.4&facet=Qualcomm%20Intelligent%20Multimedia%20SDK) 

#### Testing and Feedback  
- Test the sample application on the RB3 Gen2 and provide your feedback.

### Task 12: Experience the IDE and Execute the sample applications inside the IDE

- [Exploration Sample apps using IDE](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-51/content-develop-your-first-application.html?vproduct=1601111740013072&version=1.4&facet=Qualcomm%20Intelligent%20Multimedia%20Product%20(QIMP)%20SDK) 
- [Explore AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70018-50/example-applications.html?vproduct=1601111740013072&version=1.4&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the IDE on the RB3 Gen2 and provide your feedback.
  
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

#### Task 14: Quick start using Qualcomm VSCode IDE 
- Download vscode ide
- Onboard eSDK ( already downloaded in Ubuntu machine) 
- Explore the AI experience app.
- Import any AI app source code , compile and push modified app via IDE. 
Check time taken to complete all steps and overall clarity and UX of the workflows

#### Task 15: Upgrade existing RB3Gen2:
- Provide GA1.2 based device to the developer. 
- Use documentation to find out commands to find QLI  version on hardware.
- Perform upgrade following documents.
- Findout hardware variant ( core or vision kit ) 
- Program CDT based on hw variant at hand .
- Confirm basic apps work .
Check time to complete, check if instructions are clear and confirm flashing worked as documented.

#### Task 16: Create a docker container with QIM SDK
- Follow steps to create a 24.04 based  docker container with QIM .
- Deploy container in RB3GEN2 and confirm functions work as per document.
