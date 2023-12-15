# Barcode_and_QR-code
We will walk you through how to make a barcode and Qr code reader with Python and Machine Learning. 
This is a great machine learning task to get started with the computer vision.

Barcodes and QR codes are very cool and interesting because they store information in a different format. 
The fun part about them is that we can’t tell what they are storing until we analyze them. 
It’s like playing a puzzle game. And another thing I love about them is that they can be part of the physical world and still connect us to the internet world.

How does the barcode and QR code reader work?
If you are wondering how barcode and QR code readers work, let’s do a little practical exercise. 
Turn on your phone camera and view the featured image from this item.
We will see a link appear, it is very easy to use. 
We will learn how to create barcode and QRcode reader with Python and Machine Learning, without wasting time, let’s get started.

I will start by installing the libraries we will need for this project and then I will start with the coding part. For this task of creating a barcode and QRcode reader with Python, I recommend using a regular code editor like VScode or Pycharm.

Getting Started
The first step is to install the following three libraries: Pillow, OpenCV and Pyzbar. Pillow is the extension of PIL, which stands for Python Image Library.

OpenCV is a well-known library, especially when working with computer vision tasks. And the last library we need is Pyzbar, a python library that will help us read barcode and QR codes. You can easily install all the libraries using the pip command.

Building Barcode and QR code Reader with Python and Machine Learning
Now the next step is to write the decode function, where most of the cool stuff will happen. The decode function will mainly do three things and can be listed as follows:


* Recognize and decode the barcode / QR code that we are going to show to the camera.
* Added information stored as text on recognized barcode / QR code.
* And finally, export the stored information as a text document.

the next step is to write the main function for building a Barcode and QR code reader with Python. Let’s create our main function:

Now let’s go through the main function above to understand what I did:

First of all, we turn on the computer camera using OpenCV. If you have an external camera, you need to change the value 0 to 1 depending on the device.
Second, we run a while loop to continue performing the decode function until the “Esc” key is pressed. Otherwise, the loop will not stop and cause problems.
Third, we launch the camera that we turned on in the first step. And then we close the application window. OpenCV does all the work, just call the methods.
Finally, we call the main function to trigger the program.
Now you can easily run the code and scan any barcode and QR code by showing the code to the camera of your laptop.

You have now created a program that reads barcodes and QR codes for you. Now you have an idea of how to use computer vision and artificial intelligence in real life. Working on hands-on programming projects like this is the best way to sharpen your coding skills.

Hope you liked this article on how to create a barcode and QR code reader with Python and Machine Learning. Please feel free to ask your valuable questions in the comments section below.
