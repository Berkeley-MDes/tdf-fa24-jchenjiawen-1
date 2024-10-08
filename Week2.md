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
