# Exploring a Minimal 2D Simulation of a Two-Wheeled Mobile Robot

Developed by: <a href="https://www.bristol.ac.uk/people/person/Paul-O'Dowd-d54e9ad6-41de-4eef-81c6-1ee227ced8dc">Paul O'Dowd</a> & <a href="https://www.bristol.ac.uk/people/person/Hemma-Philamore-c3c8acb0-fcce-4792-9249-2efccb92145f">Hemma Philamore</a>. 

Welcome to the exercise sheets!  All of these exercise sheets are intended to be used interactively within <a href="https://research.google.com/colaboratory/">Google Colab</a>.  You should be able to save them into your own workspace.  You may need a <a href="https://www.google.com/account/about/">Google account</a> to do so.  

These exercise sheets are intended to provide a very quick introduction to the general frame of thinking required when working in robotics.  This includes:
- Developing control software which runs iteratively, and without end.
- To anticipate that whilst a very good solution to a task is possible, the task can easily be made more challenging.
- To appreciate that the complexity of a task and therefore suitable solutions can increase very quickly.  

These exercise sheets challenge you to move through a set of tasks which build upon the last, with escalating complexity. These are:
1. Obstacle Avoidance Behaviour
2. Circumnavigation Behaviour
3. Navigation for Mapping (coverage)
4. Following another robot with noisy sensors.

These exercise sheets serve as a brief introduction, so you are given the freedom to be creative and to explore the nature of the problem space.  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github//paulodowd/GoogleColab_Simple2DSimulator/blob/main/TestSheet.ipynb)  **Test Sheet:** You can quickly test you can access Google Colab and these exercise sheets by clicking the button on the left. 

<br><br>
## Info: Getting Started

If you have not used Python of Google Colab before, the following exercise sheets will help you to get started:

### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/01_Operators.ipynb) [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/01_Operators.ipynb) Python: Operators 
Performing basic calculations, Making comparisons between variables, Using comparisons and other Boolean True or False values to form logic statements.

### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/02_Control_Flow.ipynb) [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/02_Control_Flow.ipynb) Python: Control Flow
Making decisions within a program to direct the flow of the program execution.
    
### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/03_Loops.ipynb) [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/03_Loops.ipynb) Python: Loops
Controllably repeating operations within a program. 
    
### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/notebooks/intro.ipynb) Google Colab 
Colaboratory, or 'Colab' for short, allows you to write and execute Python in your browser, with Zero configuration required, Free access to GPUs, & Easy sharing.  Whether you're a student, a data scientist or an AI researcher, Colab can make your work easier.

### Jupyter / Anaconda:
If you cannot access Google Colab, then you may wish to install Jupyter/Anaconda on your own computer to run these files locally.   You will also need to download the files from this github repository.
<a href="https://test-jupyter.readthedocs.io/en/latest/install.html">Install Jupyter/Anaconda</a>

A short how-to on running these sheets within Anaconda/Jupyter is <a href="https://github.com/paulodowd/GoogleColab_Simple2DSimulator/raw/main/anaconda_instructions.pdf">available here</a>.

<br><br>

## [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/Sheet1_ObstacleAvoidance.ipynb) Day 1: Obstacle Avoidance

<table>
  <tr>
    <td>
<img src="https://github.com/paulodowd/GoogleColab_Simple2DSimulator/blob/main/img/obs_avoidance.png?raw=true" width="350px">
    </td>
    <td>
      In this worksheet we will develop a controller to make decisions for the simulated robot.  You can investigate using python to read the simulated sensors and to steer the robot away from obstructions.
    </td>
  </tr>
 </table>

<hr><br><br>

## [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/Sheet2_Circumnavigation.ipynb) Day 2: Circumnavigation

<table>
  <tr>
    <td>
<img src="https://github.com/paulodowd/GoogleColab_Simple2DSimulator/blob/main/img/c_navigation.png?raw=true" width="350px">
    </td>
    <td>
      In this worksheet we will develop a more advanced controller for the simulated robot.  You can write behaviours for the robot to discover an obstruction and then to control the simulated robot to navigate around the obstruction at close proximity.
    </td>
  </tr>
 </table>

<hr><br><br>

## [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/Sheet3_Mapping.ipynb) Day 3: Mapping

<table>
  <tr>
    <td>
<img src="https://github.com/paulodowd/GoogleColab_Simple2DSimulator/blob/main/img/mapping.png?raw=true" width="350px">
    </td>
    <td>
      In this worksheet we will combine previous work to record a map of the simulated environment.  You will need to develop a strategy and an advance controller to explore the environment efficiently.
    </td>
  </tr>
 </table>

<hr><br><br>

## [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/paulodowd/GoogleColab_Simple2DSimulator/blob/main/Sheet4_SensorNoise.ipynb)  Day 4: Sensor Noise


<table>
  <tr>
    <td>
<img src="https://github.com/paulodowd/GoogleColab_Simple2DSimulator/blob/main/img/Following.png?raw=true" width="350px">
    </td>
    <td>
      In this worksheet we explore the challenges of a real sensor, the Pololu SDS02A.  The simulator has been updated and you are challenged to write a controller to follow another robot.  
    </td>
  </tr>
 </table>
 
<hr><br><br>

## Day 5: Explore!

We've kept this day free of a new exercise sheet so that you can explore any of the previous sheets and take them further if you wish.  You'll be able to ask for support on any related questions during the teaching session.


