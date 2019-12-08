# Mini Project 3 <br/>
#### The repo for the third mini project under EC601 - Product Design in ECE course at Boston University. <br/><br/>
#### Topic - Mobile Machine Learning <br/>
#### Introduction
Mobile machine learning has come a long way in the last few years. These days, with the advent of powerful mobile hardware, it has become possible to develop mobile applications with powerful machine learning features like face recognition or text completion. There are two leading frameworks for this purpose, CoreML for Apple Devices, and MLKit for iOS and Android devices. Mobile ML presents unique challenges, like limited memory and power, and speed requirements. The algorithms need to be optimized for speed, as mobile use cases generally require instantaneous feedback.
#### CoreML <br/>
CoreML is Apple's proprietary framework for embedded machine learning inference inside Apps on Apple devices like the iPhone, Apple Watch etc. Models can be developed using either the proprietary CreateML format from the XCode IDE or converted to this format from supported frameworks like PyTorch or Tensorflow. It is more mature of the two frameworks, and was released earlier. <br/>
#### MLKit <br/>
MLKit is Google's proprietary framework for embedded machine learning inference on Android and iOS devices. It uses a Firebase backend for model training. Inference can be done either locally or via the cloud. It has superseded Tensorflow lite, which was designed for use in low power devices, such as mobile phones. <br/>
