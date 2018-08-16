# Old Project

I started programming back when I was in grammar school. Starting in 1999 with
I soon dived into various progamming languages and tried out what I could get
into my hands.
It started with Java Script, where I happened to pick up a book from my fathers
library by accident. Soon I moved to Visual Basic 6 and then Java.
Wanting to better understand how everything works under the hood, I had to add
x86 assembler to that list, before I started to settle for a bit with C++.

My first 'real' programming project then was a joint thesis project with two
class mates.

## [Elektron (2002)](Elektron/Elektron.md)

![Elektron teaser image](Elektron/Elektron_quarter.png){:.align-left}

Having not the slightest clue how difficult it would turn out, we convinced our
teacher that we would develop a cross-platform (Windows 9x, MacOS 9)
simulation program for simple
[analog circuits](https://en.wikipedia.org/wiki/Electronic_circuit#Analog_circuits).

Elektron allows the user to draw and configure an analog circuit by dropping
components onto a drawing canvas, move them around, connect them to other
components and configure their properties.
The designed circuits can be simulated and the changing properties observed by
reading virtual power meters or the brightness of LEDs and lights.

Used technologies: *CodeWarrior, C++, Win32, Carbon*

## Queue (2005)

![Queue teaser image](Queue/Queue_half.png){:.align-left}

As part of the software engineering class, we designed and implemented a game.
In a small team of four, we built a 3D billiard game.
It features a realistic physics engine and supports different billiard variants.
The popular [8-Ball](https://en.wikipedia.org/wiki/Eight-ball) two-player mode
and a time based single player mode, called ETH-mode.
The graphics engine and the HUD use OpenGL and both are completely in 3D.

Used technologies: *EiffelStudio, SVN, Eiffel, OpenGL*

Used concepts: *Business Object Notation (BON)*

## Digital Circuit Simulation (2005)

![Full adder](Circuit/FullAdder.png){:.align-left}

Digital circuit design was fun. Towards the end of the semester I was wondering
if it would be possible to build a simulator for simple circuit designs using
C# delegates. The answer is, yes. Delegates allow to let any change to the input
be automatically trickled to the output.

Used technologies: *Visual Studio, C#*

## From Eiffel to C# (2005)

Believes are strong motivators to do things. And back in the summer of 2005 I
believed that I had to tell my university collegues that C# was better than
Eiffel, the language we were using in lectures. So, I organised a small workshop
and prepared some slides and written documenation. In order to get some practice,
my 'students' had to implement a small UI application within a small framework.

## Gravity Bound (2007)

One part of my graduate program in Visual Computing was to delve into game
programming. Back in 2007 Microsoft offered a new game development API called
XNA for cross-platform game development on Windows and the Xbox 360 using C#.
The was designed as a 3D split-screen multiplayer game similar to the 2D game ...
Each player was controlling an oil blob with which he should collect points by
eating little animals...
As an additional challenge you could rotate the world, wich would make all the
game items 'fall down'. The oil blobs however to stick themselves to the walls.
The oil blob was simulated using a constrained-based soft-body concept, where
the internals of the blob was built as a volumetric mesh. The simulation of
several blobs was computationally challenging on the Xbox 360 as the SIMD units
where not accessible through C#.
The quality of the 3D content remained very limited as no one on our team
seemed to be skilled enough for 3D modelling.

Used technologies: *Visual Studio, C# (compact profile), XNA (D3D9), SVN*

Used concepts: *Constrained-based soft-body simulation*

## Auto-vectorizer (2007)

During my time as computer science student I attended a basic and an advanced
compiler design class. While the former was focused on language parsing,
intermediate representatin generation and code generation, the advanced class
focused on code transformation and optimization using the Static Single
Assignment (SSA) form. As part of this class, together with a friend, I
implemented an automatic loop vectorizer, which turned SISD into SIMD code.

![Auto-vectorizer pipeline](AutoVectorizer/pipeline.png){:.align-left}

Due to time constraints, we did not manage to more than the basics, these
however very successfully. We managed to properly unroll and vectorize simple
loops.

Used technologies: *Java, GNU Assembler (GAS), SVN*

Used concepts: *Single Instruction Multiple Data (SIMD), Static Single Assignment (SSA)*

## Dark Physics (2007)

One part of the 'Physically-based Simulation' lecture was to apply the theory
to practice. In a small team of three, we developed a rigid-body simulation
engine, which supported different primitives types (plane, sphere, oriented box)
and contact resolution based on the separating axes test (SAT). In order to use
the available computational power optimally, the collision detection was
separated into a board and narrow phase.
As an additional challange, we wanted to properly support resting contacts.
Allowing objects to stack properly without vibrating at the contact poinst
required to have a solver for the linear complementary problem (LCP).

Used technologies: *Visual Studio, C#, XNA (D3D9), SVN*

Used concepts: *Rigid-body physics, Separating Axes Test (SAT), Linear Complementarity Problem (LCP)*

## Raytracer (2007)

Used technologies: *Visual Studio, C++, Visual Source Safe*

Used concepts: *Ray-tracing*

## Real-time Wavelet Turbulence Simulation (2008)

Used technologies: *Visual Studio, C++, CUDA, SVN*

Used concepts: *Single Instruction Multiple Data (SIMD), Parallelization, Concurrency*
