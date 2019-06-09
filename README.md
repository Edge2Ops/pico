# The Pico Project

Object Detection & Analysis Made Simple using Raspberry Pi, Apache Kafka, AWS Rekognition & Docker

![alt text](https://github.com/collabnix/pico/blob/master/images/thepicoproject1.png)



## What is Pico Project all about?



Imagine you are able to capture live video streams, identify objects using deep learning, and then trigger actions or notifications based on the identified objects - all using Docker containers. With Pico, you will be able to setup and run a live video capture, analysis, and alerting solution prototype.

![alt text](https://github.com/collabnix/pico/blob/master/images/pico-project-arch.png)

A camera surveils a particular area, streaming video over the network to a video capture client. The client samples video frames and sends them over to AWS, where they are analyzed and stored along with metadata. If certain objects are detected in the analyzed video frames, SMS alerts are sent out. Once a person receives an SMS alert, they will likely want to know what caused it. For that, sampled video frames can be monitored with low latency using a web-based user interface.

The Pico framework uses Kafka cluster to acquire data in real-time. Kafka is a message-based distributed publish-subscribe system, which has the advantages of high throughput and perfect fault-tolerant mechanism. The type of data source is the video that generated by the cameras attached to Raspberry Pi. 





## What Technologies does Pico uses?

![alt text](https://github.com/collabnix/pico/blob/master/images/image-9.png)

- Apache Kafka
- Docker
- Docker Swarm
- AWS Rekognition Service

## Why Apache Kafka & not AWS Kinesis?

- Kafka is amazingly fast.  
- Quite easy to operate & simple to configure.
- Vey low memory and CPU footprint.
- Stable
- Provides you DIY capability
- Open Source



## Preparing Your Environment

|Items        |   Link        | Reference  |
| ------------- |:-------------:| -----:|
| Raspberry Pi 3 Model B| [Buy](https://robu.in/product/latest-raspberry-pi-3-model-b-original/) | ![Buy](https://github.com/collabnix/pico/blob/master/images/pibox.png) |
| Raspberry Pi Infrared IR Night Vision Surveillance Camera Module 500W Webcam | [Buy](https://robu.in/product/raspberry-pi-infrared-ir-night-vision-surveillance-camera-module-500w-webcam/) | ![Buy](https://robu.in/product/raspberry-pi-infrared-ir-night-vision-surveillance-camera-module-500w-webcam/)| 


![alt text](https://github.com/collabnix/pico/blob/master/images/rasp_cluster.jpg)
- Buy Raspberry Pi (Tested with Rpi 3) 
- Buy Heat Sink(Optional)
- Buy Pi Camera Module 
- Buy Pi camera Tripod Stand(Optional)
- Raspberry Pi 3 Model B 4-layer Dog Bone Stack Clear Case Box Enclosure 
- AWS Rekognition Access (Free tier) 

## Getting Started

Stage I - [Installing Docker on Raspberry Pi](https://github.com/collabnix/pico/tree/master/getting-started)<br>
Stage II - [Turn Your Raspberry Pi into Night survillience Camera using Docker]()<br>
Stage III -  [Deploy Apache Kafka on AWS Platform using Docker Swarm]()<br>
Stage IV- [Pushing the video frame from Raspberry Pi to Apache Kafka[() -WIP<br>
Stage IV - []() - TBD<br>



