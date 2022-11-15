# Data Driven Control for navigation planning

The repository contains three main folders:

* **SalernoScenario** contains the urban scenario of Salerno centre validated in SUMO.
* **UnisaScenario** contains the digital twin of the University of Salerno validated in SUMO.
* **UnisaHIL** regards the Hardware-in-the-Loop validation that took place in Fisciano Campus (University of Salerno).

Each folder is organized as follows:

* **agent.py** contains the class definition for an Agent object (the term agent refers to the controlled car by control algorithm).
* **crowdsourcing.py** contains the class definition for a Crowdsourcing object, which is characterized by the decision-making function implementation.
* **crowdsourcing.py** contains the main script to test the crowdsourcing algorithm on the corresponding scenario.
* **utility.py** contains utility functions such as reward functions, rerouting functions etc.
* **create_behaviors.ipynb** is the Jupiter Notebook that creates the target behaviors for the crowdsourcing algorithm.
* **Simulationlauncher.ipynb** is the Jupiter Notebook that creates the controlled and uncontrolled cars sets and run simulations in SUMO.
* **plots.ipynb** is the Jupiter Notebook that allow to obtain diagrams and evaluation metrics to validate the crowdsourcing algorithm.

## How to use:

1. Configure and run **create_behaviors.ipynb**
2. Configure **demo_crowds.py**
3. Configure and run **Simulationlauncher.ipynb**
4. Configure and run **plots.ipynb**
  