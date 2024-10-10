# Outline
[week 1](README.md#Week-1)

[week 2](README.md#Week-2)

[week 3](README.md#Week-3)

[week 4](README.md#Week-4)

[week 5](README.md#Week-5)

[week 6](README.md#Week-6)

---
# Week 6
## What I did this week
### Soldering
It's my first time doing soldering in the past 10 years.\
<img src="/Week6/IMG_2040.jpeg" width ="500" align="center">

### Stemma
1. Accelerometer and gyro. This time we didn't have a breadboard diagram for connection, but I successfully connected the components based on guessing according to the codes.(I'm pretty happy because I know very little about coding and engineering).
<img src="/Week6/IMG_2046.jpeg" width ="800" align="center">

2. However, the LED blinks too frequently and it makes me blind. So I added a delay(3000), and now it's just right.
<img src="/Week6/3s.gif" width ="800" align="center">

3. Proximity. Success on the first try.
<img src="/Week6/proximity.png" width ="800" align="center">

4. Color. Successful but I wasn't sure how to test if the sensitivity is satisfying.
<img src="/Week6/color.png" width ="800" align="center">

### Team and Draft Proposal
I continued with my teammates for the Big Idea Contest, and we'd like to use this assignment as a feasibility test for our potential prototype for the BIC.\
<img width="800" alt="image" src="https://github.com/user-attachments/assets/d6cf87ff-2495-4e79-ba9d-01206fb58163">

## What I thought about this week
We really have too many deadlines and housekeeping work(also for other classes). It stops me from thinking... I have less energy and time to think week by week...

## Speculation of next week
We will focus on the project and make our first trial.

---

# Week 5
## What I did this week
### YouTube Tutorials
Since I'm completely new to microcontrollers, I watched 2 YouTube tutorials to get some basic knowledge and revive my previous knowledge of electronic circuits.\
[Arduino for Beginners](https://www.youtube.com/watch?v=JnJIKX5J0Cc&list=PLwWF-ICTWmB7-b9bsE3UcQzz-7ipI5tbR)\
[Full Programming Workshop in 90 Minutes](https://www.youtube.com/watch?v=BLrHTHUjPuw&t=64s)

### In-class tutorial
1. I connected the breadboard according to the fritzing, but the LED didn't light up.
 <img src="/Week5/in-class-03-fail.jpeg" width ="500" align="center">
 
2. I moved the lead from D3 to D7, and it worked.
<img src="/Week5/in-class-03-suc.jpeg" width ="500" align="center">

### Button send on change
1. I connected the circuit as in the tutorial, but it didn't work at first.
<img src="/Week5/basic-button-soc_fail.jpeg" width ="500" align="center">

3. I noticed that's because my button is 2-pin instead of 4-pin, so I fixed the connection accordingly, and it worked.
<img src="/Week5/basic-button-soc_suc.jpeg" width ="500" align="center">
<img src="/Week5/basic-button-soc2.png" width ="500" align="center">

### FSR to LED Color
1. It gave me a flash error, there shouldn't be any problems in the code and connection.
<img src="/Week5/flash error.png" width ="500" align="center">
3. I Tried a few troubleshooting but none worked. Then I noticed the Photon LED light was not blinking which may be abnormal. So I unplugged and replugged the Photon. Then it flashed successfully.
<img src="/Week5/IMG_2034.gif" width ="500" align="center">

### Accelerator to Servo
1. I connected through halfway and wasn't sure if I had the correct ADXL 362, I will check with the TA.
<img src="/Week5/IMG_2032.jpeg" width ="500" align="center">

2. I also wanted to try the potentiometer to OLED, but there is no potentiometer in my kit... I will double-check with the TA.
3. Additionally, I don't have a JST cable that has 4 separate outputs.

### Button to LED Pulse
1. Finally it was successful on the first try.
<img src="/Week5/2.jpeg" width ="500" align="center">


## What I thought about this week
I can follow the tutorial and understand the logic of the code. However, I sure can not write/make something from scratch. I browsed some basic tutorials online but those take time. Did someone mention a copilot feature in VSCode? 

## Speculation of next week
I would like to know more about the final project of this module so that I can get more prepared.

---

# Week 4
## What I did this week
1. According to the lecture on Monday, I drew a simple diagram of the trash & recycling system. It's not digital right now, but could have a great potential to be digital.
I want to show how the "useless" materials were recycled and repurposed. In a consumer society, a large amount of waste is generated every day. Despite this, people continue to purchase new items, believing that old ones are no longer useful, and casually throw them into the trash.\
<img src="/Week4/diagram.png" width = "1000" ></img>

2. I also finished the report for Project 1.
3. I took a look into Photon 2. I have never used it or Arduino. 


## What I thought about this week
1. Capitalism created a lot of waste.
2. There are apps like "Too Good to Go" to save food waste.
3. Besides recycling, how can we prevent waste from being produced? 

## Speculation of next week
Learn more about Photon 2 through class and online tutorials.

---

# Week 3
## What I did this week
### Design system
For assignment 1, I'm thinking of designing a system that helps every unique hand use a regular pen. It's a pen grip that transfers the dimension of the hand, including length, width, and gripping strength into Grasshopper parameters. I’d like to use 3d printing for prototyping and iteration.
I referenced an online tutorial when I encountered difficulty in making the triangular polyhedron.  
<img src="/Week3/diagram.png" width ="1000" align="center">


### 3D printing
I 3d printed 3 times this week...
The first was supposed to be a draft model with PLA. However, the reference I used was in the wrong units. Therefore the printouts are huge and not usable at all.\
<img src="/Week3/IMG_1920.jpg" width ="500" align="center">

Then I scaled it to the right size and tried with another material - flexible resin. For my design, it would be good if the pen grip is somewhat elastic. I used the Form 3 printer in the Advanced Lab, and this is the first time I have worked with this kind of printer. But this attempt was not that successful either, because I put too many support materials on a tiny object.
Informed by these two attempts, the third one was successful. \
<img src="/Week3/IMG_1924.jpg" width ="500" align="center">
<img src="/Week3/IMG_1949.jpg" width ="500" align="center">


### Video making
I hope to tell a story with my video, so I started with why I have this idea and documented all of my efforts, including the failures. 
<img src="/Week3/video.jpg" width ="500" align="center">

## What I thought about this week
1. I wish I had more time for research. I believe parametric design, or computational design relies heavily on research works. How to define the criteria? How to transfer them into parametrics? But with a very limited time, I almost had to skip the research part and get straight into design/production. So the system includes a lot of guessing and eyeballing. I think my quick test is enough to show the idea, but a deeper understanding of the ergonomics of hands is required to make a practical design system.
2. The cleaning after using Form 3 (or other resin printers) could take long.
3. It's normal to take 2-3 rounds until get a successful printout/prototype.


## Speculation of next week
I will finalize the video and write the project report for this assignment.

---

# Week 2
## What I did
### Sample file experiments
1. I read through the sample grasshopper file and drew a diagram of my understanding of how it works.\
   <img src="/Week2/0906 - Example GH Diagram.jpg"></img>
   
2. I tweaked some of the parameters. The major intention was to find the minimum size of the sample design that could still meet the manufacturing standard.\
<img src="/Week2/9.jpg" width = "500"></img>

3. When it's too small, there is a gravity problem.
4. The smallest shape I found is as below.\
<img src="/Week2/7.jpg" width = "500"></img>

### Using the sample file to generate a new design
1. I tried to take a look at the packaged GH script, hoping I could understand and revise it. But unfortunately, it's too complicated for me to understand. I will just use it as it is.\
<img src="/Week2/13.jpg" width = "800"></img>

2. I wanted to try out a polyhedron phone stand. So the first step is to build a basic shape.
3. I went with the Voronoi shape, which I was more familiar with from my previous architectural design experience.\
<img src="/Week2/6.jpg" width = "500"></img>
<img src="/Week2/11.gif" width = "500"></img>

4. I started with importing a cube from Rhino to quickly test my script. Once the script worked, I replaced the input cube with a short script that generates a cube in GH directly.\
<img src="/Week2/4.jpg" width = "500"></img>

5. I successfully generated a polyhedron base! So I merged it back to the example file and got a cell phone stand.
<img src="/Week2/3.jpg" width = "500"></img>

6. Because Voronoi is random, most of the time the center of the generated polyhedron doesn't match with the center of the cell phone.\
<img src="/Week2/2.jpg" width = "500"></img>

7. I added a move command, now It's good enough for my little test. I named it "Obsidian".\
<img src="/Week2/12.gif" width = "500"></img>
<img src="/Week2/1.jpg" width = "500"></img>

## What I thought about
1. The Grasshopper script was super intricate, I'm sure I can't write it from scratch although I have some experience with it.
2. I still like the idea of making a cell phone stand that is not for using cell phones all the time, but to reduce the usage of cell phones. But it's absolutely the opposite of what "computational design" is. Have to ditch the idea, but maybe recycle it someday.
3. What is the best "object" to be designed through a computational process? 

## Speculation of next week
Find a suitable subject for computational design.

---

# Week 1
## What I did this week...
**1. Set up Ultimaker 3 and Form 3**\
The last time I used a 3d printer was 5+ years ago. So it's great to go through all the instructions again. Also, now the 3d printers are better and more materials are available.

**2. Check out Rhino and Grasshopper example files**\
I was a landscape architect, so I have been working with these two tools for half of my lifetime.

**3. 3D Print out something**\
I randomly chose to print an egg separator (and also very useful in the kitchen!). Because of the time, I downloaded a .stl file from the Internet and made the 3D printing file. The printing is still in progress, I will add images to this report if it finishes before 3 pm.
![Screenshot of Rhino](/Week1/Egg.jpg)

I found many websites have free 3d printing-ready models for downloading.\
[Cults](https://cults3d.com/en)



## What I thought about this week...
A phone stand... That's a tiny thing, and there are more than many well-made products on the market. How can I be more innovative with a very limited time?

**Adding**
1. Phone stand + speaker?
2. Phone stand attaches to iPad, laptop, or monitor.
3. Phone stand + selfie taker.

Reference images:\
![phone with ramen bowl](/Week1/iphonebowl01.jpg)

![phone with bed](/Week1/bed-phone-stand.jpg)

**Minimizing**
1. Ultra thing and portable phone stand.
2. Foldable phone stand.
3. A magnetic phone stand to be stuck on surfaces. For example, street poles.

**Manifesto**
1. When people need a cell phone stand, their hands are occupied, but they need to look at the phone. What if my phone stand is ***NOT*** designed for people to ***look at the phone ALL THE TIME***? but to be away from the cell phone?
![people using phone or phone using...?](/Week1/ramen-bowl-with-chopsticks-through-mobile-phone-.jpg)
   
3. A bulky phone stand, and not portable at all.
4. A phone stand for ***PHONE***, instead of cell phones.

Reference images:
![test](/Week1/1.jpg)

![test](/Week1/s-l650.jpg)

![test](/Week1/antique-phone-linda-covino.jpg)

![test](/Week1/Actor_portraying_Alexander_Graham_Bell_in_an_AT&T_promotional_film_(1926).jpg)

## Lessons learned...
1. The self serviced 3d printing(aka UberEats of 3D printing) is convenient, but not many machines are available! I haven't figured out how to queue yet... Probably it's not allowed. So next time leave at least 2 days for that.
2. Github markdown is not user-friendly. Adding an image and video is inhumane...


## Other things I found may be related...
["Innovative" rediscovery of landline phone](https://www.tiktok.com/@weirdochicken/video/7204142032053488942?lang=en)



## Quick Links, compiled here for your convenience: ##

- [TDF Wiki](https://github.com/Berkeley-MDes/24f-desinv-202/wiki) - the ultimate source for truth and information about the course and assignments
- [Google Drive Folder](https://drive.google.com/drive/u/0/folders/1DJ1b6sSDwHXX6NRcQYt10ivyQSgU0ND6) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1537533) - where the grading happens
