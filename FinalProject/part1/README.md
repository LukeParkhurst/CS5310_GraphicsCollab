# Final Project - Computer Graphics

<img src="./media/header.jpg">

## Description

An important part of any computer graphics course, in my opinion, is having the opportunity to build a project that you care about. The final project in this course showcases your creativity from what you have learned over the semester and can be used as a portfolio piece for future internship, co-op, and full-time job opportunities.  We have covered enough computer graphics now that you are ready to design and create a project from scratch.
  
## Expectations

You can work on any idea you want that is within the scope of graphics (OpenGL, WebGL, Vulkan, DirectX, etc.). You may explore areas that we did not cover heavily in class (Animation, particles, different rendering techniques, advanced shaders, image processing, volume rendering, etc.).  Your final project should be on the order of the difficulty beyond the homeworks.  
## Project Ideas

I am going to list a few project ideas that I think are within the scope of this class.

* Procedural generation
  * Terrain rendering [https://www.youtube.com/watch?v=QjTPIbJNO6I]
  * City [https://www.youtube.com/watch?v=-d2-PtK4F6Y]
  * Continuous LOD [https://www.youtube.com/watch?v=DUxAyfuJULc]
* Rendering 
  * Photon maps [https://www.youtube.com/watch?v=GckOkpeJ3BY]
  * Radiosity [https://www.youtube.com/watch?v=8i2M255Zw9I]
* Constructive Solid Geometry
  * [https://www.youtube.com/watch?v=-nWPZgxYW-k]
* Extend Ray Tracer(Our final homework): [https://www.youtube.com/watch?v=ijqaBhyXN98]
  * Depth of field
  * Motion blur
* Modeling
  * Progressive Mesh https://www.youtube.com/watch?v=CcomX9UQO1w
  * Subdivision of surfaces [https://www.youtube.com/watch?v=g1M2y1bZOPw]
  * Or the opposite decimation (mesh simplification) [https://www.youtube.com/watch?v=AvSgHhA9yP4]
  * Deformable mesh [https://www.youtube.com/watch?v=r_rkSi8VZj0]
* Volume rendering
  * Example [https://www.youtube.com/watch?v=nmdlGlJ-2G0]
* Animation
  * Flocking behavior [https://www.youtube.com/watch?v=1svKGmGCdXk]
  * Inverse kinematics [https://www.youtube.com/watch?v=uN_pR9fH-WY]
  * Physics-based simulation (e.g. pinball)
  * Collision detection [https://www.youtube.com/watch?v=ZU5PKXxTv8k]
* Particle Simulation [https://www.youtube.com/watch?v=RMfsdUKEmDo]
* Games
  * Build a little First person perspective(shooter, advenutre, etc.) or other interactive environment
  * Racing game [https://www.youtube.com/watch?v=SVzFWnadOdY]
* Shaders
  * Create a world with many different shaders
    * Cel / Toon shaders [https://www.youtube.com/watch?v=RWTQuvXm2HU]
    * Bump / Normal / Parallax / Relief mapping [Example]
  * Deferred rendering [https://www.youtube.com/watch?v=HIrq4sF5QO8]

### Assignment strategy

My suggested strategy for this project is to:

* You will have plenty of time to think about the project you want to deliver, but get started early.
* I recommend finding at least one web tutorial, youtube talk, etc. that can serve as a reference for you to fall back on.
* You can get feedback from me ahead of time on nearly any graphics related topic, do so!
* Find your teammates(teams of up to 2) early if you choose to work in a team!
  * Piazza is a good resource, and I will tentatively match folks on a spreadsheet.
  
### How to run your final project

Use a [build.py](./build.py). You can modify [build.py](./build.py) to your needs, but I should be able to type `python build.py` and then run the generated executable. I plan to spend 0 time figuring out what dependencies to download. If there is some setup extraneous setup needed to run your project, we should arrange to demonstrate your project during office hours. 

Pretend you are deploying this software to someone who has no idea what your code does and needs to be able to run it. The only assumption you should make is the user has SDL2 setup and perhaps a web browser. Logistically, using the [build.py](./build.py) that we have used in this course makes it possible for myself and the course staff to run and debug your project.

### Video Deliverable

For this project, you need to make a video recording of your project. Here are the specifications:

- Give an 2-3 minute overview of your implementation as a youtube video.
- Explain what your project is (i.e. You should be talking in your video as you show things)
- Show what was achieved (e.g. moving a camera around and talking over) 
- In the video highlight **one** particular technical achievement.
  - e.g. Part of the code or algorithm that does something neat or was difficult to get right.
    - Give a quick 'tutorial' like summary of how you solved the problem.
    - You can talk about other important features in your project, but dedicate some time on one specific item.
    
Videos may publicly be uploaded to the course websites 'hall of fame'--please keep the links up!

#### Sample Video Deliverable

Here is a sample from previous years and what I like about it:

- https://youtu.be/cGB8C6IT8eE
  - I like this sample because:
    - I can hear the speakers voice.
    - The talk is well outlined and concise.
    - The speaker shows off the technical parts of the code well.
    - The speaker shows the actual visuals and uses a high resolution video.
    - It is not a very long video with lots of silence or 'umms'
    - If I were to see this on a resume, I would have a very good idea of what the developer knows.

### Deliverables

* You need to commit your code to this repository.
* Your program needs to compile using a build.py script (Unless it is a webgl project).
* Put a link to a youtube/vimeo video in this README.md.


## More Resources

* N/A

## Other FAQ

- Q: May I upload my final project to a public repository after the semester is over?
- A: Yes under the following conditions
  - You acknowledge your team members and any third parties fairly for their contributions.
  - You remove the README.md provided with the assignment (delete it entirely from your github history), as you'll want your own readme anyway.
- Q: May I have a team of 3 or 4--I really want 3 or 4 team members?
- A: No. I recommend a team size of 1-2. This project can be completed as a 1 person project.

