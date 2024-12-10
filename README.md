# LDC-Reclaimers

## About
This project, under the working title "Reclaimers", is a building generator implemented in Rhino Grasshopper, with a strong emphasis on busy, irregular megastructures, and a very low emphasis on functionality; it aims for an aesthetically pleasing and creative believability.

The name is in reference to Ana Aragão's "Vertical Reclamation of Individual Spaces" series, which greatly inspired this project. Please do check out her art at https://www.anaaragao.com/. 

Version 1.4's implementation already includes many of the basic features intended for the system, namely the basic building generation and its respective customizable parameters, as well as the basis for a customizable and expandable module system.

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
- In the Rhino console, initialize Grasshopper by executing the "Grasshopper" command. The Grasshopper interface should open.
- Open the "tokyo1.4.gh" file in the Grasshopper interface.
  - At this point, the program should start running automatically. Give it some time to let it run for the first time.
- Once that's done, everything should be ready to start using the system. :)

## Usage

To generate your first (and hopefully not last) building:

- Open the Grasshopper Remote Control Panel (Go into "View -> Remote Control Panel" in the Grasshopper interface). A window like this should open:

- Most buttons and sliders are explained and can be used through the Remote Control Panel. However, in case it hasn't appeared, or in case you wish to look through my admittedly meandering code, you can guide yourself by the instructions in the image above (although you'll have to look for the sliders/buttons by their names).


