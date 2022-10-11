# joseph-summer-2021
Code developed during time at the lab.
Check the slides to see what each code generally does: 
Google Slides link: https://docs.google.com/presentation/d/1Bw1qLDBshhGf-ZRgqw8r45XWc5xUw_MCcSGTjpMxi78/edit?usp=sharing

Binarized MNIST images in 28x28 matrices were used as input for the neural network. 
The code analyzed the attributes of resulting generated edge weight data, including:
  - Edge weight over time
  - Change in edge weight for each edge 
  - Average slopes of each label (MNIST digits) per edge basis
  - # of activations per time window in the simulation
  - LDA was used to visualize data onto euclidean space
  - KNN on the LDA data to see if clustering was significant (to see if edge space could be       used to improve classification in substitution of feature space--which was not the case).
  - Data visualization and analysis of excitatory/inhibitory edge weights
  - experimentation of neural network simulators and use of monitors to gather data. 

Errors present in code are due to not running the codes sequentially or because the input data was later changed (# of instances used); these errors were not corrected due to the time required to fully run each code sequentially in perspective of the data (10,000 instances of 10/100 node networks, etc.). 
