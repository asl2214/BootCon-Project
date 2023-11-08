# Overview

Topic: File Carving and Foremost

Goal: introduce a new Kali Linux tool called Foremost with some background in file carving
Demonstration: Demonstrating how to use Foremost

Part 1 – Research

The first part of my research that I did was to find a Kali Linux tool that was not discussed in our forensics module. Foremost happened to be one that I was able to procure off of a 
huge list. My digging led to a whole new world of file carving and it inspired me to introduce the topic and present it to my peers who are interested in other fields of cybersecurity. 

Part 2 – File Carving

Defining the details of file carving became a bit of a task due to forensics using terminology interchangeably. It then became my goal to fully define and separate **file carving* 
and the term **data carving* to its details in order to emphasize how Foremost is a data carving tool rather than a file carving tool. 

Part 3 – Creating the USB bit-stream image

The hardest part of this project was actually figuring out how to make a bit-stream image on a Windows computer that would work with a Linux command. I dug the trenches of the 
internet and traversed through the muds of forensics to have finally found my answer of using an executable dd command on powershell (We love the internet). It was both the worst and best learning moments in
knowing that I did have the ability to figure out how to power through and utilize my searching skills and being able to create an executable file through trial and error but it 
definitely felt like a part of my lifespan was taken to have found the answer. At this point, I genuinely thought about changing my whole presentation to talk about how the eff to
use a FTK imager (a blessing that i found in my delirious state of finding answers) but decided that I've come too far to even try and think about something else. I've also learned, from this process, 
that formatting a disk drive permanently erases any history on it. Yeah, a kali linux tool nor an FTK imager isn't going to be able to save a formatted disk. I also realized that if you click the wrong 
options when you format a disk, you can absolutely make it unreadable until you make it readable. Also, 2 GB flash drives are no longer sold in stores which is kind of a bummer but a necessary evil. 
So, the summary of this process is that yes, I was successful in creating a bit-stream image of a USB flash drive but it took an odyssey to get there. 

Part 4 – Project Preparation

I transferred the bit-stream image from my Windows desktop to our class Ubuntu VM that we use. Testing out Foremost was actually a charm. It tasted of sweet success and a victory lap
to the kitchen for a good 'ole reward of soda. Although, I did end up creating multiple bit-stream images and deleting ones that I didn't think would show the power of the tool. 
Always read the man pages of those Kali Linux tools, people. Even though it kinda hurts. At first, the bit stream image I had some text files, a jpg image, and some png images but 
I realized that txt files are not recovered using Foremost because it's not a support file type. I had to throw in some .doc files and a .zip file to really show the whole utility
of it and not show some measly 2 folders labeled jpg and png, especially when it's so much more than that. After some back and forth, I made sure to repeatedly demonstrate it 
and talk myself through it to not feel so anxious about how my demonstration would go live. My instructor would always caution with Murphy's Law with some "in theory" and "you coooould" 
 when he did put out that we can record our demonstrations but I decided to ride the wave of a live demonstration. 

I put together a slide deck as best as I can with the given advice of "don't put so much text", "avoid blocks", and "make sure it looks good aesthetically" and ended up choosing
something basic as heck to go with it. Plus, I couldn't forget Clippy and the various images of ClipArt as an old 2000's nostalgia and support. 
And so, the table of contents of my presentation ended up as: 
+ Cover: File Carving using Foremost
+ What is File Carving?
+ Common Techniques
+ File Carving vs Data Carving
+ Demonstration
+ Summary

