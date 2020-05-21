# Deep-Q-Networks
This is a linux implementation of a unity environment where the agent has to learn to collect bananas. The implemented code is a deep Q neural network.

# Local Installation
1) Clone or download this repo : https://github.com/udacity/deep-reinforcement-learning/tree/master/
2) Then download the environment and unzip it into this folder : https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation
3) Make sure all of the files including the agent , navigation and model are in the same folder.
4) Then you are good to go.

# Required Libraries
1) Matplotlib - pip install matplotlib. 
2) Numpy - pip install numpy
3) PyTorch - https://pytorch.org/get-started/locally/

# Environment Details

Number of agents: 1

Number of actions: 4

States look like: [ 1.              0.              0.              0.              0.84408134      0.              0.

                    1.          0.          0.0748472   0.          1.          0.          0.
                    0.25755     1.          0.          0.          0.          0.74177343
                    0.          1.          0.          0.          0.25854847  0.          0.
                    1.          0.          0.09355672  0.          1.          0.          0.
                    0.31969345  0.          0.        ]
  
States have length: 37

# Running the Code
After following the above instructions go to your jupyter-notebook and open Navigation.ipynb. Then go to the cell option in the menu bar and select run all.

You can also choose to update the hyperparameters and try training the agent yourself.



