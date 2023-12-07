<img src="./images/eduni_logo.png"  height="100" align="left"> <img src="./images/epcc_logo.jpg" align="right" height="100">

<br /><br /><br /><br /><br />

# Met Office MPI course (December 2023)

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

The world's largest supercomputers are used almost exclusively to run
applications which are parallelised using Message Passing. The course
covers all the basic knowledge required to write parallel programs
using this programming model, and is directly applicable to almost
every parallel computer architecture.

Parallel programming by definition involves co-operation between
processors to solve a common task. The programmer has to define the
tasks that will be executed by the processors, and also how these
tasks are to synchronise and exchange data with one another. In the
message-passing model the tasks are separate processes that
communicate and synchronise by explicitly sending each other
messages. All these parallel operations are performed via calls to
some message-passing interface that is entirely responsible for
interfacing with the physical communication network linking the actual
processors together. This course uses the de facto standard for
message passing, the Message Passing Interface (MPI). It covers
point-to-point communication, non-blocking operations, derived
datatypes, virtual topologies, collective communication and general
design issues.

This course will be run over two days, slightly shortert than the
normal three-day format, usinga variety of methods including formal
lectures, practical exercises, programming examples and informal
tutorial discussions. This enables lecture material to be supported by
the tutored practical sessions in order to reinforce the key concepts.

<h3>Intended Learning Outcomes</h3>

On completion of this course students should be able to:

 * Understand the message-passing model in detail.

 * Implement standard message-passing algorithms in MPI.

 * Debug simple MPI codes.

 * Measure and comment on the performance of MPI codes.

 * Design and implement efficient parallel programs to solve
regular-grid problems.

Pre-requisite Programming Languages:

C, C++ or Fortran. The course does not cover the details of how to use
MPI from Python.

<h2>Message Passing Programming with MPI</h2>

<p><strong>Dates: </strong>7th - 8th December 2023
<p><strong>Location: </strong>Met Office, Exeter</p>


<h3>Timetable</h3>

<h4>Thursday 7th December</h4>

<ul>
<li>    09:30 Message-Passing Concepts
<li>    10:15 Practical: Parallel Traffic Modelling
<li>    10:45 Break
<li>    11:15 MPI Programs
<li>    12:00 MPI Programs on Cirrus
<li>    12:15 Practical: Hello World
<li>    12:30 Lunch
<li>    13:30 Point-to-Point Communication
<li>    14:15 Practical: Pi
<li>    15:00 Break
<li>    15:30 Communicators, Tags and Modes
<li>    16:15 Practical: Pi / Ping-Pong
<li>    17:00 Finish
</ul>

<h4>Friday 8th December</h4>

<ul>

<li>    09:30 Pi Solution
<li>    10:00 Non-Blocking Communication
<li>    10:30 Practical: Message Round a Ring
<li>    10:45 Break
<li>    11:15 Practical: Message Round a Ring (cont)
<li>    12:00 Collective Communication
<li>    12:30 Lunch
<li>    13:30 Practical: Collective Communication
<li>    14:00 Overview of Virtual Topologies and Derived Data Types
<li>    14:30 Case Study
<li>    15:00 Final Optional Session: Finish Exercises / Individual Consultancy
<li>    16:00 Close

</ul>

<h3>Lecture Slides</h3>

<p><blockquote>Unless otherwise indicated all material is Copyright
&copy; EPCC, The University of Edinburgh, and is only made available
for private study. </blockquote></p>

Note that currently these are slides from a previous run of the course
and may be updated between now and December 7th.

<h4>Day 1</h4>

<ul>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L00-overview_3day.pdf">Overview of MPI course</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L01-mpconcepts.pdf">Message-Passing Concepts</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/E01-traffic.pdf">Parallel Traffic Modelling</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/road-solution.pdf">Parallel Traffic Modelling: solution</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L02-intro.pdf">MPI Programs</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L03-archer2-cirrus-mpi.pdf">MPI on Cirrus and ARCHER2</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L04-pt2pt.pdf">Point-to-Point Communication</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L06-modetagcomm.pdf">Communicators, Tags and Modes</a>
</ul>

<h4>Day 2</h4>

<ul>

<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L07-nonblocking.pdf">Non-Blocking Communication</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L08-collective.pdf">Collective Communication</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L09-topology.pdf">Virtual Topologies</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L10-derivedtypes.pdf">Derived Data Types</a> 

</ul>

<h4>Day 3</h4>

<ul>
<li><a href="https://b.socrative.com/login/student/">MPI Quiz: enter <b>HPCQUIZ</b> as the "Room Name"</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L11-casestudy.pdf">Case Study</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L12-tipsandtricks.pdf">MPI Tips and Tricks (includes dynamic memory allocation in C and array syntax issues in Fortran)</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/slides/L13-scaling.pdf">MPI Scaling (not delivered as part of this course but included for reference)</a>
</ul>

<h3>Notes</h3>

<ul>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/notes/MPP-notes.pdf">MPI course notes (historical)</a>
</ul>

<h3>Exercise Material</h3>

<p><blockquote>Unless otherwise indicated all material is Copyright &copy; EPCC, The University of Edinburgh, and is only made available for private study. </blockquote></p>

<ul>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/exercises/road.pdf">Traffic modelling exercise sheet</a></li>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/exercises/Cirrus-MPI-cribsheet.pdf">Instructions for logging on, compiling and running MPI jobs on Cirrus</a></li>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/exercises/MPP-templates.tar">Useful files and pieces of code: MPP-templates.tar</a></li>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/exercises/MPP-exercises.pdf">MPI exercise sheet</a></li>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/exercises/MPP-pi.tar">Detailed solutions to pi calculation example</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/exercises/MPP-solutions.tar">Simple example solutions to all exercises</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/exercises/MPP-casestudy.pdf">Case Study exercise sheet</a></li>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/exercises/MPP-casestudy.tar.gz">Case Study source code</a></li>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/exercises/MPP-caseserial.tar">Simple Case Study solutions (serial)</a></li>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/exercises/MPP-casesolns.tar">Simple Case Study solutions (parallel)</a></li>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/exercises/MPP-arralloc.tar">Code for dynamic array allocation in C</a>
<li><a href="https://github.com/EPCCed/MetOfficeTrainingDec23/raw/main/MPI/exercises/MPP-traffic.tar">Serial and parallel solutions to the traffic model</a></li>
</ul>

<h3>Installing MPI locally</h3>

Note that all registered users will be given access to the ARCHER2
system. Although having MPI installed on your laptop may be
convenient, do not worry if these instructions do not work for you.

<h4>Linux</h4>

Linux users need to install the GNU compilers and a couple of MPI packages,
e.g. for Ubuntu:

    user@ubuntu$ sudo apt install gcc
    user@ubuntu$ sudo apt install openmpi-bin
    user@ubuntu$ sudo apt install libopenmpi-dev

<h4>Mac</h4>

Mac users need to install compilers from the Xcode developer
package. It is easiest to install MPI using the Homebrew package
manager - here are [Instructions on how to install Xcode and
Homebrew](https://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/).

Now install OpenMPI:

    user@mac$ brew install open-mpi

<h4>Windows</h4>

Rather than installing MPI locally, we recommend that Windows users
access ARCHER2 using
[MobaXterm](https://docs.archer2.ac.uk/user-guide/connecting/#windows).

If you want to try local access to MPI, one solution is to install a
Linux virtual machine (e.g. Ubuntu) and follow the Linux installation
instructions above.

I know that some users have been able to install MPI compilers and libraries natively on Windows using the [Intel® oneAPI HPC Toolkit](https://software.intel.com/content/www/us/en/develop/tools/oneapi/hpc-toolkit.html)

---

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

