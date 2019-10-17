This repo contains my code for Concurrency-Lesson 1 project in the Object Oriented Programming Course of the Udacity C++ Nanodegree Program.

Starter code, as well as all the content below, was provided by Udacity.

-------

#Project Tasks

    Task L1.1 : In the base class TrafficObject, set up a thread barrier in its destructor 
    that ensures that all the thread objects in the member vector _threads are joined.

    Task L1.2 : In the Vehicle class, start a thread with the member function drive 
    and the object this as the launch parameters. Also, add the created thread into the _thread vector of the parent class.

    Task L1.3 : Vary the number of simulated vehicles in main and use the top function 
    on the terminal or the task manager of your system to observe the number of threads used by the simulation.

You can find these tasks in the project_tasks.txt within the workspace as well.
Build Instructions

To run this code using a Udacity workspace, you will need to use the virtual desktop. In the desktop you can use Terminator or the terminal in Visual Studio Code.

Once in the virtual desktop, to compile and run the code, create a build directory and use cmake and make as follows:

mkdir build
cd build
cmake ..
make
./traffic_simulation


