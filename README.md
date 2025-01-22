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
- [Overview of the RB3 Gen2 Development Kit and its components]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-115/dev-kits.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)
- Overview of the IQ-9100 Beta Evaluation Kit. (Contact Qualcomm staff for the preview document)

### What is in the Box  
- [Detailed explanation of the components in the Vision kit](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-253/getting_started.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)  

### Setup and Configuration  
- Laptop setup:
- If using Windows Laptop follow instructions [here](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-253/set_up_the_device.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f#panel-0-0-1).
- If using Ubuntu Laptop, following instructions [here](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-253/set_up_the_device.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f#set-up-the-ubuntu-host)
- If using a Macbook , follow steps [here](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-253/set_up_the_device.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f#panel-0-0-2)
  

## Build procedures:
#### Introduction to Qualcomm BUILD systems 

- [Overview of Qualcomm build system and user profiles](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-254/introduction.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)  

### Task 1: Download and build source code  for RB3Gen2 using QSC Launcher.
The goal is to download Qualcomm software using tools and build it and eventually program an existing RB3Gen2 with compiled software.
This task needs a Ubuntu workstation.
#### Reference 
- [QSC workflows](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-254/build_from_source_qsc_gui_intro.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)  
#### Testing and Feedback  
- Program the compiled build on RB3Gen2 and provide your feedback.

### Task 2: Download and build source code  for IQ8 Chipset using QSC Launcher.
The goal is to downlod Qualcomm software using git and program an existing RB3Gen2 with the compiled software.
This task needs a Ubuntu workstation.
#### Reference
- [github flow for unregistered developer](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-254/github_workflow_unregistered_users.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)  
#### Testing and Feedback  
- Program the compiled build on RB3Gen2 and provide your feedback

### Task 3: Download and build source code  for IQ9 Chipset using QSC Launcher.
The goal is using an approved account of Qualcomm to download sources for the IQ9 Beta Development Kit. 
Qualcomm will provide credentials to use for download of the sources.
This task needs a Ubuntu workstation.
#### Reference 
- Follow steps from the pre-downloaded preview document provided to you by Qualcomm Staff 
#### Testing and Feedback  
- Program the BSP image on IQ-9100 Beta Evaluation Kit.

## Focused AI/ML Development 
Dedicated development utilizing the Multimedia and AI SDKs on the Qualcomm Linux platform.

### Setup and Configuration  
- To save time contact Qualcomm Staff to get the Platform ESDK.
- For Windows Laptop : Follow the steps [here](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-41/getting-started.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f) to enable a Ubuntu environment for your application development and copy the SDK to it.

### Task 4: Explore AI hub and integrate model from AI hub into existing Sample Application.
- Download InceptionV3 or any other latest model, Convert and quantize the model using Qualcomm Neural Processing SDK to DLC and run the model using IMSDK based sample app.
  
#### References
- [Overview of AI Developer workflow]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-15B/aiml-developer-workflow.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)  
- [Exploration of the AI sample applications](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-50/ai-ml-sample-applications.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

### Task 5: Bring new model to AI hub (BYOM) and integrate model into existing Sample Applications (supported models in IMSDK)
- The goal is to use an face detection model (provided by Qualcomm) and write or modify an existing application to run face detection on camera stream.

#### References
- [Overview of AI Developer workflow]( https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-15B/aiml-developer-workflow.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f)
- [Object detection Sample app](https://git.codelinaro.org/clo/le/platform/vendor/qcom-opensource/gst-plugins-qti-oss/-/blob/imsdk.lnx.2.0.0.r2-rel/gst-sample-apps/gst-ai-object-detection/main.c?ref_type=heads)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

### Task 6:  Setup QAIRT SDK, Compile & Optimize an AI model using SNPE. Integrate into existing Sample Application
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

### Task 8: Develop Application in Python
#### Introduction to QIM SDK
- [Overview of QIM SDK](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-50/overview.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)  
- [Python Sample applications](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-50/python-sample-applications.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)   

#### Hands on Development  
- Run the prebuilt python application.
- Customize and run python samples.

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and share your experience/feedback in the excel.

## Explore Sample and Experience application.
The goal is to setup the Qualcomm Reference hardware provided and the  Host PC and explore the capablities of the hardware .
### Task 9: Explore existing sample application on RB3Gen2.

- [Exploration Experience application ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-253/demo_app.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f) 

- [Explore AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-50/example-applications.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the RB3 Gen2 and provide your feedback.
  
### Task 10: Explore  sample application on IQ-9100 Beta Evaluation Kit.

- [AI and Multimedia applications ](https://docs.qualcomm.com/bundle/publicresource/topics/80-70015-50/example-applications.html?vproduct=1601111740013072&versionId=35c3bc73-6ae0-4179-b66b-a01844b5a87f&facet=Qualcomm%20Intelligent%20Multimedia%20SDK)

#### Testing and Feedback  
- Test the application on the IQ-9100 Beta Evaluation Kit and provide your feedback .

### Task 11: MM Usecases -1

### Task 12: MM Usecases -2

### Task 13: MM Usecases -3
