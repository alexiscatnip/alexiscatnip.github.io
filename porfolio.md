---
layout: default
permalink: /portfolio/
---
# Portfolio

---

## Personal project - [Raindrop Viewer](https://github.com/RaindropViewer/RaindropViewer)

<img src="https://raw.githubusercontent.com/RaindropViewer/RaindropViewer/main/docs/image/game.jpg">

I'm making a unity app, for Android phones to connect to the ancient Secondlife and OpenSimulator virtual worlds. 

For years now, the Secondlife user base has been moaning and pestering linden lab about the lack of a client to connect to Secondlife on smartphones. Existing mobile clients are limited to text and chatting only. Not much 3D. 

I too wanted a more fully fleshed out client, so I started this idea in 2020 and have been tinkering with it since.

Since the most up-to-date client library [LibreMetaverse](https://github.com/cinderblocks/libremetaverse) is written in C#, I decided to start the project with Xamarin Android. But eventually changed to Unity Engine  because it was less fussy and easier to get stuff up and running. 

Recently, there are news on the Lindens side that they are developing an official mobile viewer. If that were true, this would be obsolete. 

---

## Internship - [Avetics](https://avetics.com)

I developed drone software.

### V-scan [download](https://play.google.com/store/apps/details?id=com.avetics.vscan)

<img src="../images/vscan2.png?raw=true"/>

An android app for DJI drones that uses machine learning to count the number of people.

The ability to detect people was initially quite poor, as the default object detection model was trained on generic images (as opposed to aerial images from a drone's view).

To solve that, we retrained the model on a [specific dataset](http://okutama-action.org/) of aerial images of people.

### RPI Sensor Array 

A Raspberry PI mounted on the drone, that sends the sensor data to the pilot.

When I was done with the first python program, I tried to refactor the 300 lines into 4 classes of their own, each representing an actual hardware device that was being consumer/producer. I failed miserably. I learnt that simple is better. 


---
## Internship - [Micron Singapore - Autonomous Vechicle Project](https://in.micron.com/about/blog/2019/august/accelerating-intelligence-harnessing-singapore-strength)


<img src="https://media-www.micron.com/-/media/client/global/images/blogs/featured-blog-post-images/2019/singapore.jpg?h=4000&la=en-IN&w=6000&rev=f19b8476807c416a9a2ad7b2f12d0980&hash=DEC4C39871489F7B14251AE8A16A675B"/>

I helped the team develop new features, such as a new braking system and health system. 

The stack was ROS and C++.

---

## Projects - Games, VR
### [Ecoverse ](https://github.com/jessicax941/cs4240-project) 

<img src="../images/ecoverse.png?raw=true"/>


A VR simulation that teaches you about your actions and its environment impacts

It was really hard to collaborate since it was a unity project, and there was only 1 headset to go around. 

I am pretty satisifed with the end result, but I think we could have added more interactions that are not "laser-pointer".

## [AR VideoPlayer ](https://github.com/alexiscatnip/cs4240_lab3/tree/master) 
### AR app for Android/IOS. It overlays a video player on images in the real world.

<img src = "../images/ar_video_player_cropped.gif" width="500">

## Projects - Software Eng
### [Dance Dance ](https://drive.google.com/file/d/17ecJp5Q0vSZ1ftSUzEVI7GfrJb4E2CSB/view?usp=sharing) 

<img src="../images/dancedance.PNG?raw=true"/>
<img src="../images/dancedance2.png?raw=true"/>

todo: find video of us dancing.

We created a wristband device to classify dance moves.

I was in charge of choosing, soldering, and programming the hardware and wearable parts. I was also looking at alot of excel time-series data to understand the characteristics and the best place to wear the sensor. 


<!-- ## [JavaAcademy - **Interpreted** Java 8 Programming Language](https://github.com/nus-cs4215/x-slang-t4-kyh-ac)

todo: create gif of this guy in action.

This one is really hard to explain...
We implemented an absurd-Java, 
On surface level, it obeys the grammar and syntax of Java8...
... but, under the hood, it actually runs in an interpreted manner, on top of the javascript runtime!!!
         -  Yes! Our js-based interpreter goes line by line (AST), storing each `Object name = new Object();` into an `env` datastructure in javascript.
         -  funny runtime errors unexpected of Java8 **will** occur
      -  Indeed, there is no compilation step, nor is there any java byte-code.
         -  There is no JVM!
      -  **We become one in the javascript singularity.**
      -  Just because you can, does not mean you should!!! -->

## [FreeTime - A timetable app written in Java](https://github.com/CS2113-AY1819S1-W13-1/main) 

todo: create gif of using this thing.

- I modified the UI to display our use case.
- I created a import/export data feature.

---

## Projects - Embedded Systems

## CG3207 - an implementation of subset of ARM-like CPU on FPGA

We implemented an ARM-like CPU on FPGA board. Following the Fetch-decode-execute-memory concept. 

To demostrate that the CPU is implemented with no serious issue (sanity checking), we then wrote 'blinky/abacus' program in ARM-like assembly language and compiled it to machine code defined by the CPU's Instruction Set Architecture (ISA) 

Loaded this machine code into FPGA to run and see output on physical LEDs.

Apparently based on the book [Digital Design and Computer Architecture: ARM Edition](https://dl.acm.org/doi/10.5555/2815529)

---

## Hackathons

### [Deepracer - AWS Asean BuildOn](https://buildonasean.com/awsdeepracer/linkId=91225082/)

todo: I have a video of training somewhere.

Champion.

Performed research on the strategies to train the simulated deepracer vehicle to race a track using Reinforcement Learning. 

I still don't really understand how it works. :P Looks like trial and error once we are beyond the theory.


---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
