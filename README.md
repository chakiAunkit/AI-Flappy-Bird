# AI-Flappy-Bird
In this project, I used a neural network called NEAT, which stands for Neural Evolution of Augmenting Topologies, which in turn is based on Evolutionary algorithm. The game was coded using PyGame. 

At first, birds are generated with random neural networks controlling them, I generate 20 birds per generation. The basic logic is using the best birds form a generation we create the 20 birds of the next generation. I created a fitness function which will decide how well a bird performs. How many pixels a single bird moves without hitting a pipe determines it fitness. 

Here, the Neural Network has three inputs. They y position of the bird, the difference between the top pipe and the position of the bird, the difference between bottom pipe and the position of the bird. These three factors decide whether a bird should jump or not. The output is a single neuron deciding where it should jump or not.

Resources:
NEAT documentation : https://neat-python.readthedocs.io/en/latest/
<br>
PyGame : https://www.pygame.org/docs/
