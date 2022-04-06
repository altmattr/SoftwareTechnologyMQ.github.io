---
layout: page
title: "Setup"
within: machine_learning
---

basic instructions for getting a RaspbarianLite image and installing the required libraries

We are going to create an embedded "detector" using machine learning techniques.  We will implement it on embedded hardware so real-time detection can be performed anywhere at any time.  Lets call this device the "spot-a-tron" (SaT)

The SaT is a Raspberry Pi  setup with the right libraries, applications, and running our machine learning models.  Much of the initial work is done and you will be working from that starting point.

The embedded hardware we are using is the Raspberry Pi, so our first step is to get a working Pi.

# Background to Raspberry Pi

Raspberry Pi is a small sized computer that can essentailly perform the same tasks as our computers at home. The device can be plugged into a monitor and controlled with a keyboard and mouse to be used as a fully functioning computer. It is low-cost, modular, and high performing, originally developed for teaching purposes for computer science students but growing into much more.

<div style="width:50%; margin:auto">
	<img src="https://upload.wikimedia.org/wikipedia/commons/f/f1/Raspberry_Pi_4_Model_B_-_Side.jpg "/>
</div>

Learn more about Raspberry Pi at these links below:
<ol>
	<li><a href="https://en.wikipedia.org/wiki/Raspberry_Pi">https://en.wikipedia.org/wiki/Raspberry_Pi</a></li>
    <li><a href="https://thepihut.com/blogs/raspberry-pi-tutorials/the-raspberry-pi-tutorial-beginners-guide">https://thepihut.com/blogs/raspberry-pi-tutorials/the-raspberry-pi-tutorial-beginners-guide</a></li>
    <li><a href="https://www.edureka.co/blog/raspberry-pi-tutorial/">https://www.edureka.co/blog/raspberry-pi-tutorial/</a></li>
</ol>


# Setting up the Raspberry Pi for SaT

Our Raspberry Pi will use a SD card as the operating system. The SD card normally uses an operating system call 'Raspbarian', which is designed specifically for Raspberry Pi's.   There are actually multiple variants of Raspbarian, the right one for us is "Rasparian Lite (32 bit)". Follow the steps below to set up the mini console onto our Raspberry Pi.
  * [Installing a Fresh Operating System](https://www.raspberrypi.com/software/)
# Using Raspberry Pi

To use Raspberry Pi, we need a monitor to view what we are doing, as well as a keyboard and mouse to control it. Follow the steps below to connect and boot up the Raspberry Pi. Make sure you have read the links at the top of the page and understand what Raspberry Pi is and how it works before completing these steps. 

<ol>
	<li>Insert the SD card into the SD card slot.</li>
	<li>Connect a monitor to the HDMI port. Make sure the monitor is connected to a wall socket and is powered on. The Raspberry Pi is still off, so you won’t see anything yet.</li>
    <li>Connect a keyboard to a USB port.</li>
    <li>If you want to connect to the Internet via Ethernet instead of WiFi, you should also plug in an Ethernet cable. The Raspberry Pi we have provided will allow to connect to Internet wirelessly</li>
    <li>Connect the power supply to a wall socket and plug in the micro USB cable. A red LED will light up on the Raspberry Pi, and on the monitor you will see the Raspberry Pi booting up. In a few moments you will see the login prompt.</li>
</ol>

You boot into any fresh Pi with
  * username: `pi`
  * password: `raspbarian` 

The only way to work in Raspabarian Lite is via the terminal.  In the next worksheet we will learn more about how to work in the terminal, but we will get a sneak preview here as we get the libraries and appliations that we need installed.

<a href="https://projects.raspberrypi.org/en">Here</a> are some resources to show all the other projects you could do with a Raspberry Pi.

## Terminal Preview

One you have logged in, type `ls` exactly as it is written here, then press enter. This will give you a list of files and directories that the Raspberry Pi holds. 

### TODO (cameron): Installing the Required Libraries/Tools

_Cameron: can you please do a fresh install on a fresh pi and check to see what needs intstalling to get it going?

If you check the code you will see the python libs. I know each of those need installing._

# Installing the camera

You have been supplied with a Pi "NoIR" camera module.  The following animation (from the offical raspberry pi website) shows how to connect it.

![https://projects-static.raspberrypi.org/projects/getting-started-with-picamera/7ab130979e77e11eb977625713823e41ebe1ae64/en/images/connect-camera.gif](https://projects-static.raspberrypi.org/projects/getting-started-with-picamera/7ab130979e77e11eb977625713823e41ebe1ae64/en/images/connect-camera.gif)

We weill need to dig a bit deeper into how to use the Pi before we can start getting images off the camera.

# Next Steps
You may have noticed we use Terminal a lot within this project. If you have not used a terminal much in the past, we recommend you make [this worksheet](https://medium.com/@grace.m.nolan/terminal-for-beginners-e492ba10902a) your next stop.  After that, move on to [Getting the Code](getting_code.html). 
 