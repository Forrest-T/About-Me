# About-Me
(WIP)
General Information about myself and my current/previous projects

## Education
* I am currently a fourth-year computer science student at the University of Washington, Paul G. Allen School for Computer Science and Engineering. I've taken a wide range of exploratory courses, and my current focus is on low-level systems development.
* In 2017-2018, I studied at the KTH Royal Institute of Technology in Stockholm, Sweden.

## Previous Experience
### Floating-Point Verification Researcher
In 2018, I worked on formal verification of floating-point arithmetic for embedded C-systems at Scania. I have an experience report available in [docs/float.pdf](docs/float.pdf). My work focused both on the application of existing open-source tools to an industrial environment, and on what we were able to prove formally when those tools were insufficient.

## Projects
### Parallelized GPU Raytracing with Acceleration Structures
At KTH, I took two courses in computer graphics, and my final project was open-ended. I worked with a partner, Pooria, and we iterated on a basic sequential raytracer implementation to make performance improvements. We first used KD-Trees to achieve more optimal sequential performance, then turned the base implementation into a parallelized GPU program using OpenCL 2.0. Finally, we combined both of our optimizations by integrating the KD-Trees with OpenCL, and ended up with a massive performance increase when combining the two. A summary of our work is available in [docs/raytracer.pdf](docs/raytracer.pdf), and the code is available on [Github](https://github.com/Forrest-T/DH2323-raytracer).
