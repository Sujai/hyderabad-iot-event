# Hyderabad / IOT Workshop

## Developing Applications on the Qualcomm Linux Platform 
A single day workshop for developers to build multimedia and AI applications. The goal is to Explore application development using Explore sample apps using QDemo and run sample AI/ML or Multimedia applications using Qualcomm Linux and Qualcomm Ubuntu platform and capture feedback on the experience.

## Scope 
### Overview 
- If you have not done so, [set up your Qualcomm ID]( https://myaccount.qualcomm.com/signup), confirm your email .This gives you access to the documentation and Qualcomm tools.
- Work on the task assigned to you. Please provide feedback as you navigate Qualcomm documentation in the excel sheet provided to you .
- Update the Feedback form (Excel) as you follow your workflow. Write down times you got lost, confused, or frustrated and, if applicable, how you resolved it.

## Introduction and Setup 
### Introduction  
Links to important hardware and software tools to be used for the workshop.
- [Overview of the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and its components](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-115/dev-kits.html?vproduct=1601111740013072&version=1.6)
- [Qualcomm VSCode IDE]( https://docs.qualcomm.com/bundle/publicresource/topics/80-79972-1/overview.html )
- [Ubuntu on Qualcomm® IoT Platforms]( https://docs.qualcomm.com/bundle/publicresource/topics/80-82645-20/landingpage.html?product=1601111740057201 )
- [Ubuntu Server]( https://documentation.ubuntu.com/server/ )

### What is in the Box  
- [Detailed explanation of the components in the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform]( https://docs.qualcomm.com/bundle/resource/topics/80-70018-263/getting_started.html#what-is-included)

### Setup and Configuration  
- Laptop setup:
- If using Windows Laptop follow instructions [here](https://docs.qualcomm.com/bundle/resource/topics/80-70020-261/iq9-ug-update-the-sw.html#panel-0-V2luZG93cw==).
- If using Ubuntu Laptop, following instructions [here]( https://docs.qualcomm.com/bundle/resource/topics/80-70020-261/iq9-ug-landing-page.html)
- If using a Macbook , follow steps [here](https://docs.qualcomm.com/bundle/resource/topics/80-70020-261/iq9-ug-update-the-sw.html#panel-0-bWFjT1M=)
  

## Build workflow:
#### Introduction to Qualcomm BUILD systems 
- [Overview of Qualcomm build system and user profiles](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-254/introduction.html?vproduct=1601111740013072&version=1.6)  

## AI Developer Workflow
Dedicated development utilizing the Multimedia and AI SDKs on the Qualcomm Linux platform.

### Task 1: Explore AI hub and integrate model from AI hub into existing Sample Application.

The objective is to utilize existing models from the AI Hub for segmentation, detection, classification, and super resolution, and to execute the corresponding applications with these models.

#### References
- [Overview of AI Developer workflow](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-15B/introduction.html?vproduct=1601111740013072&version=1.6)
  
#### Testing and Feedback 
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and share your experience/feedback in the excel.

### Task 2: Bring new model to AI hub (BYOM) and integrate model into existing Sample Applications (supported models in IMSDK)

Try to get the latest open-source object detection model and utilize the AI Hub ‘Bring Your Own Model’ feature to convert and optimize it for Qualcomm SoCs. Integrate the optimized model into the application and execute it, as described in the previous step.

#### References
- [Overview of AI Developer workflow](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-15B/introduction.html?vproduct=1601111740013072&version=1.6)
- [Integrate AIHUB Models](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-15B/develop-your-own-application-im-sdk.html?vproduct=1601111740013072&version=1.6)
  
#### Testing and Feedback 
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and share your experience/feedback in the excel.


### Task 3: Setup QAIRT SDK, Compile & Optimize an AI model using SNPE/QNN Integrate into existing Sample Application

- Download InceptionV3 or any other latest model, Convert and quantize the model using Qualcomm Neural Processing SDK to DLC and run the model using IMSDK based sample app.
- Download InceptionV3 or any other latest model, Convert and quantize the model using Qualcomm AI Engine Direct SDK to BIN and run the model using IMSDK based sample app

#### References
- [Overview of AI Developer workflow](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-15B/introduction.html?vproduct=1601111740013072&version=1.6)
- [Explore AI Sample applications](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-15B/ai-ml-reference-apps.html?vproduct=1601111740013072&version=1.6)

#### Testing and Feedback  

- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and share your experience/feedback in the excel.

### Task 4: Experience One-click launcher and execute sample application from One Click launcher using on-device camera & USB camera

- [Experience application using One Click launcher](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-263/iq9-run-sample-applications.html)
- [Explore AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/example-applications.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and provide your feedback.

## Python App Development
### Task 5: Develop Application with Python API of Gstreamer
#### Introduction to QIM SDK  
- [Overview of QIM SDK](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-51/qmi-sdk-qsg-landing-page.html?vproduct=1601111740013072&version=1.6&facet=Intelligent_Multimedia_SDK.SDK.2.0)
- [Installing QIM SDK on QLI Yocto](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-51/qmi-sdk-qsg-landing-page.html?product=1601111740057201&facet=Intelligent_Multimedia_SDK.SDK.2.0#panel-0-UXVhbGNvbW0gTGludXg=)
- [Python samples](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-50/python-sample-applications.html?vproduct=1601111740013072&version=1.6&facet=Intelligent_Multimedia_SDK.SDK.2.0) 

#### Hands on Development  
- Use host based development and push the file through adb and verify.  

#### Testing and Feedback  
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and share your experience/feedback.

#### QIM SDK on Ubuntu
- [Installing QIM SDK on Ubuntu](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-51/qmi-sdk-qsg-landing-page.html?product=1601111740057201&facet=Intelligent_Multimedia_SDK.SDK.2.0#panel-0-VWJ1bnR1)  
- [Python samples](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-50/python-sample-applications.html?vproduct=1601111740013072&version=1.6&facet=Intelligent_Multimedia_SDK.SDK.2.0) 

#### Development on Ubuntu
- Explore the ontarget development of QIM applications on IQ9 with Ubuntu OS.

#### Testing and Feedback  
- Test and compare the experience between Ubuntu and QLI (Yocto)

## Run All Sample Apps
### Task 6: Explore existing sample Applications on IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform – GST Sample Applications, and Python Sample Applications

- [Exploration Experience application ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-253/run-sample-apps-qdemo.html  ) 

- [Explore AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/example-applications.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)
  
#### QIM QSG on Ubuntu
- [Explore and run sample applications](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-51/content-develop-your-first-application.html?vproduct=1601111740013072&version=1.6&facet=Intelligent_Multimedia_SDK.SDK.2.0&state=releasecandidate)

#### Testing and Feedback  
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and provide your feedback.


## Using the Qualcomm VSCode IDE for Application development
### Task 7: Experience the IDE and Execute the sample applications inside the IDE with QLI1.6 (Yocto) & Ubuntu

- [Exploration Sample apps using IDE]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-51/content-develop-your-first-application.html#develop-using-qualcomm-visual-studio-code-extension) 
- [Explore AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70020-50/example-applications.html?vproduct=1601111740013072&version=1.5&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the IDE on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform/Robotics RB3 Platform and provide your feedback.
- [Exploration Experience application ](https://docs.qualcomm.com/bundle/publicresource/topics/80-79972-1/quick_start.html#panel-0-0-1 )
### Task 7.1: Create your own application build it and deploy in device.
### Task 7.2: Profile your models in AIHUB.

#### Testing and Feedback  
- Test the IDE on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and provide your feedback.

## MM Tasks
### Task 8.1: Video encode with RTSP/MIPI Camera using Gstreamer commands

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to achieve the task (Encoding video with data from camera stream).
- [Encoding video with data from camera stream](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-50/gst-camera-single-stream-example.html?vproduct=1601111740013072&version=1.6&facet=Intelligent_Multimedia_SDK.SDK.2.0&state=preview&versionId=73e1dcbd-dcd4-4288-8a0c-ee69f3c5fec3)


Note:
#### For IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform: <br>
#### RTSP camera : <br>
Supported. Please check RTSP camera is connected to IQ-9075 Evaluation Kit (EVK) (IQ-9075) .<br>
#### MIPI camera:<br>
Supported. Camera sensors are attached to device by default.<br>
#### USB camera:<br>
Supported. Please check USB camera connected on IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform device.<br>
 
 
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
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075) and provide your feedback.


### Task 8.2: Audio decode and encode using GStreamer application (IQ-9075 Evaluation Kit (EVK) (IQ-9075))

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to load the required pre requisites and do audio encode and decode at GST level.
#### Reference
- [Audio Video Encode](https://docs.qualcomm.com/bundle/publicresource/topics/80-70022-50/gst-audio-video-encode.html?vproduct=1601111740013072&version=1.6&facet=Intelligent_Multimedia_SDK.SDK.2.0)


#### Testing and Feedback  
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and provide your feedback.


### Task 8.3: Measure the KPI/ Concurrency for Camera while trying task 8.1

The goal is to setup Qualcomm Profiler and information on how to use use it to collect system-wide performance profiling metrics.
User must run some complex programs that expose the capabilties of the IQ9 processor and use Qualcomm Profiler to check the KPI.

#### References
- [Qualcomm Profiler User Guide](https://docs.qualcomm.com/bundle/resource/topics/80-54323-2/getting-started.html?state=preview)
- [Qualcomm Profiler CLI for Linux](https://docs.qualcomm.com/bundle/resource/topics/80-54323-3/getting-started.html)

#### Testing and Feedback  
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and provide your feedback.

## Video Task
### Task 9.1: Video playback using GST command

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to perform video playback using GST commands.
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075) provide your feedback.


### Task 9.2: Offline Video decode using V4l2 test app (Host PC Kernel >v6.6)

The goal is to setup the Qualcomm Reference hardware provided and use Qualcom documentation to perform  offline decode using v4l2 apps.
No documentation reference provided.Expect engineeer to  navigate to findout the instructions.

#### Testing and Feedback  
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075) provide your feedback.
- Test the application on Ubuntu server OS as well.

### Task 10.1: Implement OpenCV rotate application with FastCV

The goal is to setup the Qualcomm Reference hardware provided and use Qualcomm documentation to perform  install pre-requisites needed to create or compile any application like the 
rotate application using fastCV.
No documentation reference provided.Expect engineeer to navigate to findout the instructions.

### Task 10.2: Measure the KPI/ Concurrency for Camera while trying task 10.1
The goal is to setup Qualcomm Profiler and information on how to use use it to collect system-wide performance profiling metrics.

#### References
- [Qualcomm Profiler User Guide](https://docs.qualcomm.com/bundle/resource/topics/80-54323-2/getting-started.html?state=preview)
- [Qualcomm Profiler CLI for Linux](https://docs.qualcomm.com/bundle/resource/topics/80-54323-3/getting-started.html)

#### Testing and Feedback  
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and provide your feedback.

#### Testing and Feedback  
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and provide your feedback

### Task 11: Graphics Task
#### Task 11.1: Weston EGL client application commands

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to test EGL client of Weston .
No documentation reference provided. Expect engineer to  navigate to find out the instructions.

#### Testing and Feedback  
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and provide your feedback


### Task 11.2: Compile and run GLES and Vulkan applications.

The goal is to setup the Qualcomm Reference hardware provided and use QLI documentation to perform GLES and Vulkan sample application.
No documentation reference provided. Expect engineer to  navigate to find out the instructions.

#### Testing and Feedback  
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and provide your feedback
### Task 11.3: Measure the KPI/ Concurrency for Camera while trying task 11.x

The goal is to setup Qualcomm Profiler and information on how to use use it to collect system-wide performance profiling metrics.

#### References
- [Qualcomm Profiler User Guide](https://docs.qualcomm.com/bundle/resource/topics/80-54323-2/getting-started.html?state=preview)
- [Qualcomm Profiler CLI for Linux](https://docs.qualcomm.com/bundle/resource/topics/80-54323-3/getting-started.html)

#### Testing and Feedback  
- Test the application on the IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform and provide your feedback.

## Upgrade Workflow
### Task 12:Upgrade existing IQ-9075 Evaluation Kit (EVK) (IQ-9075)
- Upgrade IQ-9075 Evaluation Kit (EVK) (IQ-9075) older software to latest version 
- Use documentation to find out commands to find QLI  version on hardware.
- Perform upgrade following documents.
- Find out hardware variant ( core or vision kit ) 
- Program CDT based on hw variant at hand .
- Confirm basic apps work .
  
## OOB experience
### Task 13 :Upgrade existing IQ-9075 Evaluation Kit (EVK) (IQ-9075)/Robotics RB3 Platform
- OOB -- Connect kbd/mouse/display/spk/wifi... & run EVK as SBC (Single Board computer).  Build an Multimedia Gstreamer basedapp 
- OOB -- Connect BT kbd/mouse/headset/ display... & run EVK as SBC. Make a call? Google Meet? 
- OOB -- Connect kbd/mouse/display/spk/wifi... & run EVK as SBC. Run a Linux network game?







Check time to complete, check if instructions are clear and confirm flashing worked as documented.
<br>
<br>
<br>
<br>
