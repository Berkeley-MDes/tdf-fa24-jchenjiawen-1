# Outline
[week 1](README.md#Week-1)

[week 1](README.md#Week-2)

---

# Week 1#
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


# Week 2 #
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


## Quick Links, compiled here for your convenience: ##

- [TDF Wiki](https://github.com/Berkeley-MDes/24f-desinv-202/wiki) - the ultimate source for truth and information about the course and assignments
- [Google Drive Folder](https://drive.google.com/drive/u/0/folders/1DJ1b6sSDwHXX6NRcQYt10ivyQSgU0ND6) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1537533) - where the grading happens
