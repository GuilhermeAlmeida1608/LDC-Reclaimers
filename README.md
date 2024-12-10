# Reclaimers

![Showcase2](/docs/showcase2.jpg)

## About
This project, under the working title "Reclaimers", is a building generator implemented in Rhino Grasshopper, with a strong emphasis on busy, irregular megastructures, and a very low emphasis on functionality; it aims for an aesthetically pleasing and creative believability.

Version 1.4's implementation already includes many of the basic features intended for the system, namely the basic building generation and its respective customizable parameters, as well as the basis for a customizable and expandable module system.

![Showcase](/docs/showcase.jpg)

## Getting Started

### Prerequisites

- Rhino 8 (I haven't tested the project on previous versions; some features may not work)
- Grasshopper for Rhino (comes included with Rhino 6 and above)
- The following Grasshopper libraries/addons:

  - [4D Noise](https://www.food4rhino.com/en/app/4d-noise)
  - [Anemone](https://www.food4rhino.com/en/app/anemone)
  - [Pancake](https://www.food4rhino.com/en/app/pancake)
  - [Metahopper](https://www.food4rhino.com/en/app/metahopper)
  - [OpenNest](https://www.food4rhino.com/en/app/opennest)
  - [Elefront](https://www.food4rhino.com/en/app/elefront)
  - [Heteroptera](https://www.food4rhino.com/en/app/heteroptera)

  *(Note that these might not all be strictly necessary for this project, but I have them all installed at the moment; since I don't know which components are specifically from which, it's better to be safe than sorry.)*

### Installation

To get the project running, you must:

- Open the "Reclaimers_repo_version.3dm" file. The scene should look like this:

![Scene Example](/docs/scene.jpg)

- In the Rhino console, initialize Grasshopper by executing the "Grasshopper" command. The Grasshopper interface should open.
- Open the "tokyo1.4.gh" file in the Grasshopper interface.
  - At this point, the program should start running automatically. Give it some time to let it run for the first time.
- Once that's done, everything should be ready to start using the system. :)

## Usage

To generate your first (and hopefully not last) building:

- Open the Grasshopper Remote Control Panel (Go into "View -> Remote Control Panel" in the Grasshopper interface). A window like this should open:

![Remote Control Panel](/docs/instructions.jpg)

(Most buttons and sliders are explained and can be used through the Remote Control Panel. However, in case it hasn't appeared, or in case you wish to look through my (admittedly meandering) code, you can guide yourself by the instructions in the image above - although you'll have to look for the sliders/buttons by their names.)

- The system also allows you to customize the initial floorplan and swap out and/or add new modules, though these take a bit more effort.
  - To change the initial floorplan, simply modify the origin-centered plane, or set a new geometry at the [Geo] node (right-click the node, click "Set one Geometry" and then the geometry you wish to change it to in the Rhino interface) in this area:
![Code1](/docs/initialfloorplan.png)
  - To swap out or add new modules, head to this section, and modify the existing modules or Shift-connect a new Referenced Geometry to the relay (add a new Geometry node, set the geometry to your module, and press Shift while dragging the connector to the relay), respectively:
![Code2](/docs/changemodules.png)

## Acknowledgements

This project was done as part of the Computational Design Lab course for the MSc of Design and Multimedia at the University of Coimbra, under the supervision of professors Tiago Martins, Sérgio Rebelo and João Cunha.
This project is greatly inspired by Ana Aragão's beautiful artworks. The project's name is in reference to the "Vertical Reclamation of Individual Spaces" series. Please do check out her art at https://www.anaaragao.com/. 

## Credits

Guilherme Almeida - Design and Development
Tiago Martins - Supervision
Sérgio Rebelo - Supervision
João Cunha - Supervision
Luísa Brito - Companionship and Banter
