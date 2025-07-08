# Verse Library

Verse is a Python library for creating, simulating, and verifying scenarios with interacting, decision making agents. The decision logic of an agent can be written in an expressive subset of Python. The continuous evolution can be described as a black-box function. The agent can be ported across different maps, which can be defined from scratch or imported from [opendrive](https://www.opendrive.com/) files. Verse scenarios can be simulated and verified using hybrid reachability analysis algorithms. The initial implementation of reachability analysis used intervals (hyperrectangles) as the main data structure. A new implementation that support generalized star sets will soon become available. Verse is developed and maintained by the [Reliable Autonomy Research Group](https://mitras.ece.illinois.edu/group.html) at the [University of Illinois at Urbana-Champaign](https://ece.illinois.edu/).

<img src="./docs/source/figs/drone-2-8.gif" height="150"/> <img src="./docs/source/figs/nondeterm_sensor.png" height="150"/> <img src="./docs/source/figs/car-ped-1.png" height="150"/>
<img src="./docs/source/figs/uam-collision.png" height="150"/>
## Installation
The package requires python 3.8+. The package can be installed using pip with all required dependencies

```sh
pip install -e .
```
To update the dependencies in case anything is missing, requirements.txt can be used.

```sh
pip install -r requirements.txt
```
Try
```sh
python3 demo/ball/ball_bounces.py
```
Try other examples in the `demo/` folder. 



