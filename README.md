# AI Nights Content - Beginner Track
## For Session Owners - Train the Trainer

This is a GitHub repository provided for **session owners** to access and learn content that can be delivered at **AI Nights** across the globe in **April and September**. This content is designed for the **Beginner Track** and is approx **2 hours worth** of content. Some elements of the workshops are for the speakers to demo and other elements are for attendees to complete on their own devices and with their own Azure Subscription. Please find the public workshop content for attendees here:  [https://github.com/amynic/AINights](https://github.com/amynic/AINights)

## Session Information 
**Session Title:** Creating applications that can see, hear, speak or understand - using Microsoft Cognitive Services

**Session Abstract:** In this workshop you will be introduced to the [Microsoft Azure Cognitive Services](https://azure.microsoft.com/en-gb/services/cognitive-services/), a range of offerings you can use to infuse intelligence and machine learning into your applications without needing to build the code from scratch. 
We will cover pre-trained AI APIs, such as [computer vision](https://azure.microsoft.com/en-gb/services/cognitive-services/directory/vision/) and [text analytics](https://azure.microsoft.com/en-gb/services/cognitive-services/directory/lang/), that are accessed by REST protocol. Then look at how you can host these [models in containers](https://docs.microsoft.com/en-us/azure/cognitive-services/cognitive-services-container-support), giving you the ability to run Cognitive Services offline and on edge devices. Finally we will dive into Custom AI that uses transfer learning - [Microsoft Azure Custom Vision](https://azure.microsoft.com/en-gb/services/cognitive-services/custom-vision-service/). This enables you to provide a small amount of your own data to train an image classification model. Wrapping the workshop up by building our custom trained AI into an application - using [Logic Apps](https://azure.microsoft.com/en-gb/services/logic-apps/) and [Power Apps](https://powerapps.microsoft.com/en-us/), tools that are ideal for proof of concepts within machine learning

**PowerPoint Slides available here:** [Creating applications that can see, hear, speak or understand - using Microsoft Cognitive Services]()


## Pre-requisites for your machine
* [Microsoft Azure Subscription](https://azure.microsoft.com/en-gb/free/)
* Laptop with a modern web browser (Google Chrome, Microsoft Edge)
* [Azure Storage Explorer - available on Windows, Linux and macOS](https://azure.microsoft.com/en-gb/features/storage-explorer/)
* [Postman, API Development Environment - available on Windows, Linux and macOS](https://www.getpostman.com/downloads/)
* Clone this repository to your local machine to gain images and code samples you need for the demos: ```git clone https://github.com/amynic/ainights-sessionowners.git```

## Session Timings

* **30 mins** - Computer Vision + Text Analytics API *(attendees - try it yourself)*
* **15 mins** - Container support for those APIs *(demonstration by speaker)*
* **5 mins** - Custom AI Options - what is transfer learning?
* **30 mins** - Custom models using Transfer Learning - Classification + Object Detection *(attendees - try it yourself)*
* **35 mins** - Build this sample into an app using Logic apps and Power Apps *(attendees - try it yourself)*
* **5 mins** - Useful links to share and finish


## Content Walk-through

### Microsoft Azure Cognitive Services - Computer Vision and Text Analytics

First show the Microsoft Azure Cognitive Services in their simplest format - within the web browser. 
** Navigate to [https://azure.microsoft.com/en-gb/services/cognitive-services/](https://azure.microsoft.com/en-gb/services/cognitive-services/)**

Talk through the options from Vision, Speech, Language, Knowledge and Search very briefly

Select **Vision** to navigate to: [https://azure.microsoft.com/en-gb/services/cognitive-services/directory/vision/](https://azure.microsoft.com/en-gb/services/cognitive-services/directory/vision/)

![Computer Vision website Link highlighted](/docs-images/computer-vision-link.JPG)

Talk through the Vision options very briefly (Scene and Activity Recognition in Images, OCR, Face Detection, Emotion Detection, Video indexer etc)

Select the **Demo** link next to **Scene and activity recognition in images** under **Computer Vision**

Talk through example image shown by default. The ability to scroll through the JSON response and pick out the objects it found, the tags it assigned and description provided for example.

![Computer Vision Example](/docs-images/computer-vision-demo.JPG)

Now select **Browse** button and upload the **cat.jpeg** image from ```sample-images/computer-vision-web-browser/cat.jpeg```

![Computer Vision Cat Example](/docs-images/cat-sample.JPG)

EXTRA: Also, select **Browse** button and upload the **city.jpeg** image from ```sample-images/computer-vision-web-browser/city.jpeg```

![Computer Vision City Example](/docs-images/city-sample.JPG)

### Microsoft Azure Cognitive Services - Text Analytics in a Container

### Microsoft Azure Cognitive Services - Custom Vision Demo

### Build Custom AI into an Application - Azure Logic Apps and Microsoft PowerApps