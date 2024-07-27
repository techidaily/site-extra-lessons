---
title: "Exploring New Frontiers in Contactless Interface Designs"
date: 2024-07-26T19:51:53.466Z
updated: 2024-07-27T19:51:53.466Z
tags: 
  - screen-recording
  - ai video
  - ai audio
  - ai auto
categories: 
  - ai
  - screen
description: "This Article Describes Exploring New Frontiers in Contactless Interface Designs"
excerpt: "This Article Describes Exploring New Frontiers in Contactless Interface Designs"
keywords: "\"Frontier Interface Tech,Contactless Interact UI,Innovate Hands-Free UI,Future Interface Tech,No-Touch UI Designs,Interface New Age Dev,Explore Free Touch UIs\""
thumbnail: https://www.lifewire.com/thmb/e3OdPe2ekhPfBH2xRv177miEbUc=/540x405/filters:no_upscale():max_bytes(150000):strip_icc()/turnofffindmyiphone-742865e7d4d64f158e9f290e09062826.jpg
---

## Exploring New Frontiers in Contactless Interface Designs

In the era of advancements, **Hand Tracking** is a fascinating technology with a great range of applications in both virtual and augmented reality.

**Hand Tracking** is a process by which a computer can analyze and interpret the movement of a person's hands. This can be done using various devices, such as smart gloves, often known as data gloves.

In this article, we’ll discuss **Hand Tracking** technology, its various applications, and how to create it using Python, OpenCV, and Media Pipe.

1. [Tracking With Interface](#part2-1)
2. [Tracking Without Interface](#part2-2)

* [Using Python, OpenCV, And MediaPipe To Create A Hand Tracking](#part3)  

1. [What is OpenCV](#part3-1)  
2. [What Is Media Pipe](#part3-2)  
3. [Guidance With Steps](#part3-3)

* [Use Filmora to demonstarte your Hand Tracking skill](#part4)

## Part 1\. What Is Hand Tracking? Where Is It Applied?

Hand Tracking refers to the process of tracking the position and movement of a user's hands in virtual reality. This is usually done using a combination of sensors, including cameras, infrared sensors, or ultrasonic sensors.

By tracking the user's hands, VR systems can provide more immersive and interactive experiences. For example, Hand Tracking can be used to allow users to interact with virtual objects, as well as to provide input for gestures and body language.

The Oculus Quest 2 is a virtual reality headset that immerses you in virtual worlds. Quest 2's one of the coolest features is Hand Tracking, which lets you interact with the virtual world around you using your hands.

With Hand Tracking, you can interact with the virtual world more naturally and intuitively. You can use your hands to pick up objects, draw, and even type on a virtual keyboard. Moreover, it opens up new possibilities for gameplay, allowing you to play games in new and innovative ways.

![hand tracking technology](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-technology.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## Part 2\. Types Of Hand Tracking

There are two main types of Hand Tracking: with interface and without interface:

### Tracking With Interface

With interface Hand Tracking, you need to use a device such as a glove or a controller to interact with the virtual world. This can be used in VR or AR applications. It is further divided into two systems:

**1\. Inertial Motion Capture Gloves**

Inertial motion capture gloves use sensors Inertial Measurement Units or IMUs with built-in sensors to track the movement of your hands. These sensors include gyroscopes, accelerometers, and sometimes magnetometers for measuring angular rate, detecting gravitational force and acceleration, and measuring the earth’s magnetic field, respectively.

These gloves can be used for a variety of purposes, such as gaming, virtual reality, and motion capture for movies and video games. Inertial motion capture gloves are becoming increasingly popular as they offer a more immersive experience than traditional controllers.

**2\. Optical Motion Capture Systems**

Optical motion capture is a process that uses cameras and reflective sensors to track movement in three-dimensional space. These systems are often used in movies and video games to create realistic animations.

Optical motion capture systems emit infrared light from the camera. The markers reflect light, which is then captured by cameras. The movement of the markers is then used to create a three-dimensional model of the object.

The more cameras used, the more accurate the results. While this technology is very precise, it can be limited by factors such as body position and movement.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Tracking Without Interface

Also known as Markerless Hand Tracking, this type of Hand Tracking allows users to track their hand movements without the need for any external markers or data gloves, meaning more spontaneous interaction and freedom of movement. This could hugely impact everything from gaming to virtual reality to human-computer interaction.

Right now, markerless Hand Tracking is still in its early stages, with a few limitations. However, as this technology continues to develop, we will likely see more and more applications for it in the future.

## Part 3\. Using Python, OpenCV, And MediaPipe To Create A Hand Tracking

Above we have learned what is Hand Tracking and the two types of it. Now let’s see how we can create a hand tracking with two Python Libraries - OpenCV and MediaPipe.

Before we go further about them, let us learn about Python quickly. Python is a versatile language used for a wide range of tasks, including image processing and computer vision. We will use Python and two Python Libraries: OpenCV and MediaPipe, to create a Hand Tracking module.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### What is OpenCV

To get a deeper understanding of OpenCV, please read our article: _Opencv Tracking, a compete review_.（同期交付文章，请插入相关内链\~）

### What Is Media Pipe

Media Pipe is an open-source framework by Google that provides a set of tools for working with multimedia data or media processing. It includes modules for handling audio, video, and images. Media Pipe also supports various codecs and file formats.

There are two stages for creating a Hand Tracking program using MediaPipe:

1. **Palm Detection**: In the first stage, MediaPipe has to work with the entire input image, providing a cropped image of the hand.
2. **Hand Landmarks Identification**: In the second stage, the framework works with the cropped image of the hand to find 21 hand landmarks.

![20 hand landmarks for identifiction – hand tracking](https://images.wondershare.com/filmora/article-images/2022/07/20-hand-landmarks-for-identifiction-hand-tracking.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Guidance With Steps

Before starting to create Hand Tracking, you need to install the [Pycharm IDE](https://www.jetbrains.com/pycharm/download/#section=windows)app on your PC. Once installed, launch it and follow these instructions step-by-step:

**Install OpenCV and MediaPipe**

Click the **“New Project”** option and select **“Create”** on the next Window. Open the **Terminal** to install the two libraries.

![install and launch the pycharm app on your pc](https://images.wondershare.com/filmora/article-images/2022/07/install-and-launch-the-pycharm-app-on-your-pc.jpg)

Copy and paste the following command in the **Terminal** to install **OpenCV:**

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![copy and paste command to install opencv](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-1.jpg)

Now, to install **MediaPipe**, copy and paste the following command:

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
![install mediapipe](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-2.jpg)

**Coding**

A _main.py_ file for writing code will be automatically created in _Pycharm_ app once you create a new project.

##### Step1 Importing The Libraries

First, import the OpenCV and MediaPipe to use their dependencies. Once done, create an object _cap_ for video capturing and three other objects; _mpHands, hands,_ and _mpDraw_ to manipulate your input using MediaPipe.

![importing the libraries](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-3.jpg)

##### Step2 Capturing And Processing An Image Input

Copy and paste the following line of code to take the image input from your PC webcam.

![capturing and processing an image input](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-4.jpg)

The image is converted to RGB from BGR because MediaPipe works with this type of image. The RBG image is then processed to track the hand.

##### Step3 Working With Both Hands

Now, create a class for tracking and for the hands function to work, key in the basic parameters. Next, provide all the initialization required. This includes the basic parameters and MediaPipe initializations. Put _“self”_ before each object to provide access to its attributes and methods.

![working with both hands](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-5.jpg)

##### Step4 Creating Method For Tracking Hands In Input Image

![creating method for tracking hands](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-6.jpg)

Afterward, use the above code to create a method for using specifically to identify hands in the input image. The code will also draw hand landmarks and hand connections.

##### Step5 Locate The ‘X’ and ‘Y’ Coordinates Of Each Hand Point

To create a method for finding the x and y coordinates of the z21 hand points and a list that you will use to keep the values of these, write the code below:

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![locate x and y coordinate of hand point](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-7.jpg)

In this method, use the code that you used to find the ID and hand landmark of each hand point. Moreover, put the code you will use to circle the hand point.

##### Step6 Main Method

Now, write the below dummy code to showcase what the module can do, i.e., identify and track hands. The code appears in the main method and uses the _lmlist object_ and _image_.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-8.jpg)

##### Step7 Main Method Execution

To execute the main method, copy and paste the following code lines:

![main method execution](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-9.jpg)

##### Step8 Result

The module and output of the program will be the same, and when they are complete without any errors, you will get your output, i.e., the module will track and identify your hand movements without any glitches.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Part 4\. Use Filmora to demonstarte your Hand Tracking skill

After what has been explained above and what you have learned by now, we hope you have been equipped with hand tracking module knowledge and be ready to take action. Here, we will also sincerely recommend you a user-friendly and professional video edtior to show your hand motion scene – [Filmora](https://tools.techidaily.com/wondershare/filmora/download/)!

[Filmora](https://tools.techidaily.com/wondershare/filmora/download/) is available for all types of users. You can easily use it to edit your video, add effects to it and insert your hand motion part naturally.

Learn more about Filmora:

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For macOS 10.14 or later

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## Conclusion

In this article, we’ve explored Hand Tracking and its two types, i.e., tracking with interface and tracking without interface. Moreover, we provided step-by-step guidance on using Python, OpenCV, and MediaPipe to create a Hand Tracking module.

We hope this guide helped resolve your queries, and you can now create a Hand Tracking module in no time. And please do try [Filmora](https://tools.techidaily.com/wondershare/filmora/download/) to create a magical video with your Hand Tracking scenes in it!

* [What is OpenCV](#part3-1)
* [What Is Media Pipe](#part3-2)
* [Guidance With Steps](#part3-3)
* [Use Filmora to demonstarte your Hand Tracking skill](#part4)

## Part 1\. What Is Hand Tracking? Where Is It Applied?

Hand Tracking refers to the process of tracking the position and movement of a user's hands in virtual reality. This is usually done using a combination of sensors, including cameras, infrared sensors, or ultrasonic sensors.

By tracking the user's hands, VR systems can provide more immersive and interactive experiences. For example, Hand Tracking can be used to allow users to interact with virtual objects, as well as to provide input for gestures and body language.

The Oculus Quest 2 is a virtual reality headset that immerses you in virtual worlds. Quest 2's one of the coolest features is Hand Tracking, which lets you interact with the virtual world around you using your hands.

With Hand Tracking, you can interact with the virtual world more naturally and intuitively. You can use your hands to pick up objects, draw, and even type on a virtual keyboard. Moreover, it opens up new possibilities for gameplay, allowing you to play games in new and innovative ways.

![hand tracking technology](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-technology.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## Part 2\. Types Of Hand Tracking

There are two main types of Hand Tracking: with interface and without interface:

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
### Tracking With Interface

With interface Hand Tracking, you need to use a device such as a glove or a controller to interact with the virtual world. This can be used in VR or AR applications. It is further divided into two systems:

**1\. Inertial Motion Capture Gloves**

Inertial motion capture gloves use sensors Inertial Measurement Units or IMUs with built-in sensors to track the movement of your hands. These sensors include gyroscopes, accelerometers, and sometimes magnetometers for measuring angular rate, detecting gravitational force and acceleration, and measuring the earth’s magnetic field, respectively.

These gloves can be used for a variety of purposes, such as gaming, virtual reality, and motion capture for movies and video games. Inertial motion capture gloves are becoming increasingly popular as they offer a more immersive experience than traditional controllers.

**2\. Optical Motion Capture Systems**

Optical motion capture is a process that uses cameras and reflective sensors to track movement in three-dimensional space. These systems are often used in movies and video games to create realistic animations.

Optical motion capture systems emit infrared light from the camera. The markers reflect light, which is then captured by cameras. The movement of the markers is then used to create a three-dimensional model of the object.

The more cameras used, the more accurate the results. While this technology is very precise, it can be limited by factors such as body position and movement.

### Tracking Without Interface

Also known as Markerless Hand Tracking, this type of Hand Tracking allows users to track their hand movements without the need for any external markers or data gloves, meaning more spontaneous interaction and freedom of movement. This could hugely impact everything from gaming to virtual reality to human-computer interaction.

Right now, markerless Hand Tracking is still in its early stages, with a few limitations. However, as this technology continues to develop, we will likely see more and more applications for it in the future.

## Part 3\. Using Python, OpenCV, And MediaPipe To Create A Hand Tracking

Above we have learned what is Hand Tracking and the two types of it. Now let’s see how we can create a hand tracking with two Python Libraries - OpenCV and MediaPipe.

Before we go further about them, let us learn about Python quickly. Python is a versatile language used for a wide range of tasks, including image processing and computer vision. We will use Python and two Python Libraries: OpenCV and MediaPipe, to create a Hand Tracking module.

### What is OpenCV

To get a deeper understanding of OpenCV, please read our article: _Opencv Tracking, a compete review_.（同期交付文章，请插入相关内链\~）

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### What Is Media Pipe

Media Pipe is an open-source framework by Google that provides a set of tools for working with multimedia data or media processing. It includes modules for handling audio, video, and images. Media Pipe also supports various codecs and file formats.

There are two stages for creating a Hand Tracking program using MediaPipe:

1. **Palm Detection**: In the first stage, MediaPipe has to work with the entire input image, providing a cropped image of the hand.
2. **Hand Landmarks Identification**: In the second stage, the framework works with the cropped image of the hand to find 21 hand landmarks.

![20 hand landmarks for identifiction – hand tracking](https://images.wondershare.com/filmora/article-images/2022/07/20-hand-landmarks-for-identifiction-hand-tracking.jpg)

### Guidance With Steps

Before starting to create Hand Tracking, you need to install the [Pycharm IDE](https://www.jetbrains.com/pycharm/download/#section=windows)app on your PC. Once installed, launch it and follow these instructions step-by-step:

**Install OpenCV and MediaPipe**

Click the **“New Project”** option and select **“Create”** on the next Window. Open the **Terminal** to install the two libraries.

![install and launch the pycharm app on your pc](https://images.wondershare.com/filmora/article-images/2022/07/install-and-launch-the-pycharm-app-on-your-pc.jpg)

Copy and paste the following command in the **Terminal** to install **OpenCV:**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![copy and paste command to install opencv](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-1.jpg)

Now, to install **MediaPipe**, copy and paste the following command:

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![install mediapipe](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-2.jpg)

**Coding**

A _main.py_ file for writing code will be automatically created in _Pycharm_ app once you create a new project.

##### Step1 Importing The Libraries

First, import the OpenCV and MediaPipe to use their dependencies. Once done, create an object _cap_ for video capturing and three other objects; _mpHands, hands,_ and _mpDraw_ to manipulate your input using MediaPipe.

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![importing the libraries](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-3.jpg)

##### Step2 Capturing And Processing An Image Input

Copy and paste the following line of code to take the image input from your PC webcam.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![capturing and processing an image input](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-4.jpg)

The image is converted to RGB from BGR because MediaPipe works with this type of image. The RBG image is then processed to track the hand.

##### Step3 Working With Both Hands

Now, create a class for tracking and for the hands function to work, key in the basic parameters. Next, provide all the initialization required. This includes the basic parameters and MediaPipe initializations. Put _“self”_ before each object to provide access to its attributes and methods.

![working with both hands](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-5.jpg)

##### Step4 Creating Method For Tracking Hands In Input Image

![creating method for tracking hands](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-6.jpg)

Afterward, use the above code to create a method for using specifically to identify hands in the input image. The code will also draw hand landmarks and hand connections.

##### Step5 Locate The ‘X’ and ‘Y’ Coordinates Of Each Hand Point

To create a method for finding the x and y coordinates of the z21 hand points and a list that you will use to keep the values of these, write the code below:

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
![locate x and y coordinate of hand point](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-7.jpg)

In this method, use the code that you used to find the ID and hand landmark of each hand point. Moreover, put the code you will use to circle the hand point.

##### Step6 Main Method

Now, write the below dummy code to showcase what the module can do, i.e., identify and track hands. The code appears in the main method and uses the _lmlist object_ and _image_.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-8.jpg)

##### Step7 Main Method Execution

To execute the main method, copy and paste the following code lines:

![main method execution](https://images.wondershare.com/filmora/article-images/2022/07/hand-tracking-9.jpg)

##### Step8 Result

The module and output of the program will be the same, and when they are complete without any errors, you will get your output, i.e., the module will track and identify your hand movements without any glitches.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## Part 4\. Use Filmora to demonstarte your Hand Tracking skill

After what has been explained above and what you have learned by now, we hope you have been equipped with hand tracking module knowledge and be ready to take action. Here, we will also sincerely recommend you a user-friendly and professional video edtior to show your hand motion scene – [Filmora](https://tools.techidaily.com/wondershare/filmora/download/)!

[Filmora](https://tools.techidaily.com/wondershare/filmora/download/) is available for all types of users. You can easily use it to edit your video, add effects to it and insert your hand motion part naturally.

Learn more about Filmora:

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/) For macOS 10.14 or later

## Conclusion

In this article, we’ve explored Hand Tracking and its two types, i.e., tracking with interface and tracking without interface. Moreover, we provided step-by-step guidance on using Python, OpenCV, and MediaPipe to create a Hand Tracking module.

We hope this guide helped resolve your queries, and you can now create a Hand Tracking module in no time. And please do try [Filmora](https://tools.techidaily.com/wondershare/filmora/download/) to create a magical video with your Hand Tracking scenes in it!

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/new-360-camera-buying-guide-how-to-choose-a-suitable-360-camera-2023-update/"><u>[New] 360 Camera Buying Guide  How to Choose a Suitable 360 Camera -2023 Update</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-before-you-fly-drone-purchase-tips-and-considerations/"><u>[New] Before You Fly  Drone Purchase Tips and Considerations</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-best-free-live-streaming-software-and-app-for-all-platforms/"><u>[New] Best Free Live Streaming Software and App for All Platforms</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-brilliant-hues-ranking-11-expert-color-correction-tutorials/"><u>[New] Brilliant Hues  Ranking 11 Expert Color Correction Tutorials</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-cinematic-mastery-starts-here-the-best-cameras-of-all-levels/"><u>[New] Cinematic Mastery Starts Here  The Best Cameras of All Levels</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-compile-of-top-15-gopro-stabilizers-and-mounts/"><u>[New] Compile of Top 15 GoPro Stabilizers & Mounts</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-cost-effective-sky-gadgets-frugal-flight-devices-ranking/"><u>[New] Cost-Effective Sky Gadgets  Frugal Flight Devices Ranking</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-deciding-on-the-best-videography-camera-type-dslr-or-mirrorless-for-2024/"><u>[New] Deciding on the Best Videography Camera Type  DSLR or Mirrorless for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-a-step-by-step-guide-for-sharing-camera-roll-pictures-on-snapchat/"><u>[New] In 2024, A Step by Step Guide for Sharing Camera Roll Pictures on Snapchat</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-ios-leading-psp-emulators-five-star-selections-for-2024/"><u>[New] IOS Leading PSP Emulators  Five Star Selections for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-navigating-instagrams-updated-feed-dynamics/"><u>[New] Navigating Instagram’s Updated Feed Dynamics</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-milestones-of-vegaspros-2019-upgrade/"><u>[New] The Milestones of VegasPro's 2019 Upgrade</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-prime-pc-emulators-for-gaming-on-retro-gb-devices/"><u>[Updated] 2024 Approved  Prime PC Emulators for Gaming on Retro GB Devices</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-timekeeping-tutorial-setting-up-a-timer-in-obs-studio/"><u>[Updated] 2024 Approved  Timekeeping Tutorial  Setting Up a Timer in OBS Studio</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-25plus-best-practices-for-crafting-witty-metaverse-visual-jokes/"><u>[Updated] 25+ Best Practices for Crafting Witty Metaverse Visual Jokes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-amplify-your-brands-impact-with-a-strategic-approach-to-smm-excellence/"><u>[Updated] Amplify Your Brand's Impact with a Strategic Approach to SMM Excellence</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-astonishing-assessment-and-alternative-choices/"><u>[Updated] Astonishing Assessment & Alternative Choices</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-best-power-packs-for-black-gopro-hero5-cameras-authenticity-confirmed/"><u>[Updated] Best Power Packs for Black GoPro Hero5 Cameras – Authenticity Confirmed</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-canons-spectral-conversion-paid-and-gratis-lut-tools/"><u>[Updated] Canon's Spectral Conversion  Paid & Gratis LUT Tools</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-create-awe-inspiring-gopro-time-lapse-cinematography/"><u>[Updated] Create Awe-Inspiring GoPro Time-Lapse Cinematography</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-discover-the-hits-top-tracks-on-spotify-for-2024/"><u>[Updated] Discover the Hits  Top Tracks on Spotify for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-step-by-step-guide-to-professional-filmmaking-via-youtube/"><u>[Updated] In 2024, Step-by-Step Guide to Professional Filmmaking via YouTube</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-prime-video-upload-solutions-for-twitter/"><u>[Updated] Prime Video Upload Solutions for Twitter</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pushing-the-envelope-in-color-correction-top-10-luts-for-lightroom-experts/"><u>[Updated] Pushing the Envelope in Color Correction  Top 10 LUTs For Lightroom Experts</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-essential-guide-to-verifying-your-youtube-profile-for-2024/"><u>[Updated] The Essential Guide to Verifying Your YouTube Profile for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-unleash-potential-in-online-collaboration-using-snap-photography-for-2024/"><u>[Updated] Unleash Potential in Online Collaboration Using Snap Photography for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unleash-your-potential-with-these-12-best-flip-screen-cameras/"><u>[Updated] Unleash Your Potential with These 12 Best Flip-Screen Cameras</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-calculating-viewing-time-for-a-20mb-video/"><u>2024 Approved  Calculating Viewing Time for a 20Mb Video</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-craft-professional-text-the-best-affects-extensions-revealed/"><u>2024 Approved  Craft Professional Text  The Best Affects Extensions Revealed</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-inbuilt-camera-functions-to-capture-screens-on-huaweis-matep-series-phones/"><u>2024 Approved  Inbuilt Camera Functions to Capture Screens on Huawei's Mate/P Series Phones</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-unveiling-the-best-practices-for-crafting-viral-instagram-reels/"><u>2024 Approved  Unveiling the Best Practices for Crafting Viral Instagram Reels</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-your-guide-to-the-best-igtv-virtuosos/"><u>2024 Approved  Your Guide to the Best IGTV Virtuosos</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024s-top-iphone-selfie-assistants-ranked-8/"><u>2024'S Top iPhone Selfie Assistants Ranked #8</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/add-shimmer-to-photos-illustrators-motion-blur-guide-for-2024/"><u>Add Shimmer to Photos  Illustrator's Motion Blur Guide for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/chuckling-chambers-humor-for-special-days/"><u>Chuckling Chambers  Humor for Special Days</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/elite-image-processor-upgrade-your-viewing-experience-for-2024/"><u>Elite Image Processor  Upgrade Your Viewing Experience for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/fast-fixes-to-skyrocket-your-podcast-live-for-2024/"><u>Fast Fixes to Skyrocket Your Podcast Live for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/fb-video-placement-upright-or-flat-angle-for-2024/"><u>FB Video Placement - Upright or Flat Angle for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-change-xiaomi-redmi-12-5g-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Xiaomi Redmi 12 5G Location on Skout | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/how-to-create-text-memes-with-meme-text-generator/"><u>How to Create Text Memes with Meme Text Generator?</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-sharefake-location-on-whatsapp-for-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-5-best-360-degree-action-cameras/"><u>In 2024, 5 Best 360-Degree Action Cameras</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-closer-look-at-apples-m1-computing-powerhouse/"><u>In 2024, A Closer Look at Apple’s M1 Computing Powerhouse</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-best-sources-for-pixel-ringtone-downloads/"><u>In 2024, Best Sources for Pixel Ringtone Downloads</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-capturing-the-thrill-hero5-black-against-hero4-silver/"><u>In 2024, Capturing the Thrill  Hero5 Black Against Hero4 Silver</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-selfie-showstoppers-adding-whimsy-with-the-cartoon-lens/"><u>In 2024, Selfie Showstoppers  Adding Whimsy with the Cartoon Lens</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/laughing-lane-the-no-10-guide-to-memelore/"><u>Laughing Lane - The No. 10 Guide to Memelore</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/narrative-nexus-cutting-edge-storytelling-channels-of-the-year/"><u>Narrative Nexus  Cutting-Edge Storytelling Channels of the Year</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-wave-for-sonys-s6700-blu-ray-player/"><u>New Wave for Sony's S6700 Blu-Ray Player</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/podcastpathfinder-charting-new-courses/"><u>PodcastPathfinder  Charting New Courses</u></a></li>
<li><a href="https://games-able.techidaily.com/smart-cooling-tech-top-choices-for-a-steam-deck-lover/"><u>Smart Cooling Tech: Top Choices for a Steam Deck Lover</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/snapseed-101-easy-steps-to-photo-perfection/"><u>Snapseed 101  Easy Steps to Photo Perfection</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/summit-elite-production-space-25/"><u>Summit Elite Production Space 25</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tips-and-tricks-to-tell-if-your-apple-iphone-xs-is-unlocked-by-drfone-ios/"><u>Tips And Tricks To Tell if Your Apple iPhone XS Is Unlocked</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-10-memetic-artistry-codes/"><u>Top 10 Memetic Artistry Codes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/ultimate-7-video-streaming-apps-your-ally-in-going-live-with-youtube-from-iphones-and-android-for-2024/"><u>Ultimate 7 Video Streaming Apps  Your Ally in Going Live with YouTube From iPhones & Android for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unlocking-creative-potential-using-luts-for-color-grading-in-ae/"><u>Unlocking Creative Potential  Using LUTs for Color Grading in AE</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-y27-5g-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo Y27 5G Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/voice-clarity-the-premier-podcast-microphones/"><u>Voice Clarity  The Premier Podcast Microphones</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/wit-warehouse-ideas-matching-every-festivity/"><u>Wit Warehouse  Ideas Matching Every Festivity</u></a></li>
</ul></div>
