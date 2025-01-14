## Wellcome To ArchaeoSimLab
This is a fork of the [DroneSimLab](https://github.com/orig74/DroneSimLab) project.

Drone lab is a multi simulation which include multiple simulation engines:  
- Software in the loop (SITL) from the ArduPilot project.  
- Software in the loop (SITL) from the PX4 project.  
- Unreal engine 4 provides imagery and depth sensor data.  

The framework is flexible and enables adding more robot simulation engines as well as other sensor simulation engines (such as UE4).

The main idea behind DroneSimLab main:  
Instead of building one simulation for robot development we are providing a framework for several simulations from different domains to interact with each other. We achieve this goal by running the engines in containers (specifically Docker containers).

## Building the DroneSimLab environment:
Please also follow the [wiki](https://github.com/orig74/DroneSimLab/wiki)

Cloning the submodules will probably fail in a timeout, so it is neccesary to map ssh calls to https like this:

`git config --global url."https://".insteadOf git://`

## Demos: 
[BlueROV2 Sim](https://youtu.be/zoSgZ6T8fT8)

[Flying Drone](https://youtu.be/4dplKATTkMw)  
[Two drones tracking](https://youtu.be/cEeUj4JF16A)    
[Underwater](https://youtu.be/B2h4Dxa31F4)

## Paper:
    @article{ganoni2017framework,
      title={A Framework for Visually Realistic Multi-robot Simulation in Natural Environment},
      author={Ganoni, Ori and Mukundan, Ramakrishnan},
      journal={arXiv preprint arXiv:1708.01938},
      ISBN = {978-80-86943-44-2},
      ISSN = {2464-4617},
      year={2017},
      note={WSCG 2017 proceedings}
    }
