# OptimalForagingRL
Implementation of the work presented in this paper: [The application of temporal difference learning in optimal diet models (Journal of Theoretical Biology, 2014)](https://www.sciencedirect.com/science/article/pii/S0022519313004189?via%3Dihub) 

Studying how wild predators learn to forage and optimize hunting strategy is an area of interest in ecology. Traditional models have included use of Monte Carlo methods or Bayesian inference, and this paper presents a reinforcement learning model-free approach to modeling a predator's learning process. Mainly, this paper models predator interactions with aposematic prey. 
<img src="https://upload.wikimedia.org/wikipedia/commons/5/56/Korreldragende-gifkikker-3.jpg" width=300>


This model is based on simple Q-learning with 1 state and 2 actions, as specified in the paper. 

The notebook `Analysis.ipynb` includes implementation, reproduction of results, and additional experimentation.
You can also view the notebook [here](https://nbviewer.jupyter.org/github/slowjazz/OptimalForagingRL/blob/master/Analysis.ipynb) if GitHub doesn't render. 
