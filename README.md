# F1_Simulation
This Python code simulates car movement using NEAT (NeuroEvolution of Augmenting Topologies) for AI learning. Cars navigate a map, avoid obstacles, and optimize fitness through neural networks and genetic algorithms.
Car Simulation with NEAT AI
This project is a car simulation that uses NEAT (NeuroEvolution of Augmenting Topologies) to evolve neural networks for controlling car movement in a 2D environment. The AI-controlled cars attempt to navigate through a track while avoiding obstacles, using sensors to detect nearby boundaries. Over generations, the cars improve their performance by evolving better strategies through the NEAT algorithm.

Features
Neural Network AI: Cars use a neural network to control movement and decision-making, adjusting their speed and steering based on radar (sensor) inputs.
NEAT Algorithm: Evolution of neural networks is managed through the NEAT algorithm, enabling cars to evolve and optimize their performance over multiple generations.
Fitness Tracking: Cars' fitness is calculated based on distance traveled, and successful avoidance of obstacles. Fitness improves across generations.
Pygame Integration: The simulation is rendered using Pygame, showing cars in real-time as they navigate the environment.
Dynamic Car Sensors: Cars are equipped with radars that sense the distance from obstacles in multiple directions, enabling them to react accordingly.
Requirements
To run the project, ensure you have the following installed:

Python 3.x
Pygame (pip install pygame)
NEAT-Python (pip install neat-python)
How to Run
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/your-repo-name.git
Install the required dependencies:

bash
Copy code
pip install pygame neat-python
Place the required images in the working directory:

car.png: The sprite for the car.
map.png: The track map the cars will navigate.
Run the simulation:

bash
Copy code
python simulation.py
The simulation will run for up to 1000 generations by default. You can adjust this in the code or configuration file.

Configuration
The NEAT configuration file (config.txt) controls various parameters like population size, mutation rates, and fitness threshold. You can tweak these settings to experiment with the behavior and evolution of the cars.

File Structure
simulation.py: Main file for running the simulation.
config.txt: Configuration file for NEAT.
car.png: Image sprite for the car.
map.png: Image file for the track map.
Customization
You can modify the following to experiment with the simulation:

Car Size/Speed: Modify CAR_SIZE_X, CAR_SIZE_Y, and speed in the Car class to change the behavior and appearance of the cars.
Track Map: Replace the map.png with a different map to change the track layout.
NEAT Parameters: Adjust the parameters in config.txt to control how the AI evolves, such as increasing the population size, mutation rates, etc.
Acknowledgments
This code was heavily inspired by the work of YouTuber Cheesy AI and further optimized and commented on by NeuralNine (Florian Dedov).

License
This project is licensed under the MIT License. See the LICENSE file for details.
