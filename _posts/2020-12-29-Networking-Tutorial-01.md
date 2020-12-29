---
toc: true
layout: post
categories: [releases]
comments: true
title: Networking Tutorial 1:- Data Communication
author: Tushar Sharma
---

# Data Communication
Data communications are the exchange of data between two devices via some form of transmission medium such as a wire cable.

## Effectiveness Of Data Communication
The effectiveness of the data communication depends on:-   
1. Delivery: Data must be received by intended user.
2. Accuracy: Accurate data should be delivered to user.
3. Timeliness: Data should be delivered in timely manner.
4. Jitter: It refers to the variation in the [packet](https://en.wikipedia.org/wiki/Network_packet) arrival.  

## Components OF Data Communication  
1. Message: Information(data) to be communicated.  
2. Sender: Device that sends the message.
3. Receiver: Device that receives message.
4. Transmission Medium: Path through which data transfers from sender to receiver.
5. Protocol: Set of rules for the transmission.
    
![data communication model](/images/data communication model.png) *Data Communication Model*   

## Data Representation   
Information today comes in different forms such as text, numbers, image, audio and video.

* Text   
Text is represented in the form of bit pattern, which is a sequence of bits (0's and 1's). Different sets of bit pattern have been designed to represent text symbols. Each set is called code and the process of designating the symbols is called coding.  
Today the prevalent coding that is being used is [*unicode*](https://en.wikipedia.org/wiki/Unicode) uses 32 bits to represent each symbol or character used in any language in the world.

*` Note:  ASCII or American Standard Code For Information Interchange constitutes of first 127 character of the unicode.  `*

*  Numbers
Numbers are also represented by bit patterns. They are also represented in a ASCII table.      

* Image
Image is composed of a matrix of pixel (image elements).The size of the pixel depends on the resolution of the pixel. Each pixel is assigned a bit pattern and the bit pattern depends on the the size of the pixel.
Size of the pixel of the image depends on the basis of there types. for example- black and white, greyscale, RGB and YCM.

* Audio 
Here audio refers to the recording or broadcasting of sound or music. Audios are alot different than the other form of data such as images, numbers and text. It is continuous not discrete even when we change it to an electrical signal we create a continuous signal.

* Video
It also refers to broadcasting but of a picture or movie. It can be both continuous entity (e.g. using a camera) or a discrete entity using a number of images where each represents a discrete entity.

## Data Flow 
There are multiple methods by which data transmission takes place between devices which varies on the need and type of our devices.
There are three types of data flow techniques which are used:
1. Simplex Mode:
   In simplex mode, the communication is unidirectional as on a one way street. Only one device on the network can send and only one device can receive the data. Simplex mode is most commonly used in devices like keyboard and mouse.  
   ![simplex mode](https://github.com/tushar2411/networking/blob/master/images/simplex.jpg)
2. Half-Dulpex Mode:
   In the duplex mode both the devices on the network can behave like sender and receiver and transmit data to each other. A common example for duplex mode are walky-talkies.    
   ![half duplex mode](https://github.com/tushar2411/networking/blob/master/images/half%20duplex.jpg)
3. Full-Duplex Mode:
   In Full-Duplex mode both the devices can perform sender and receiver task either ways but unlike half duplex they can perform tasks simultaneously.A common example of full duplex mode is the telephone network. When two individuals are talking to each other on a telephone network they can talk and listen at same time.  
   ![full duplex mode](https://github.com/tushar2411/networking/blob/master/images/full%20duplex.jpg)

*`So that is it for our first tutorial of computer networking,`*  
*`In next tutorial we will learn about networks.`*  
*`please do share your suggestions and feedback in comments.`*














