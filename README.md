# BrainBench 2vs2 software package
This software package is used for evaluation of word vectors. The online service of BrainBench and the paper can be found here:
http://www.langlearnlab.cs.uvic.ca/brainbench/
## Installation
1. Make sure Python 2.7 is installed on your computer.
2. Run "pip install requirements.txt" to install the required packages to run the software

## Usage
The program takes word vector in txt files as input.
The format of the input file should be as following:

airplane 1.118059 -1.600544 1.137621 ...

beetle 0.301896 -0.068586 -0.129543 ...

To run the program, do "python two_vs_two.py yourVector.txt"
The program will run approximately 30 seconds, and then result will be shown.

Pre-trained Vectors can be found here:
http://www.langlearnlab.cs.uvic.ca/brainbench/#pretrained_vectors
