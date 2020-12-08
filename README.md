# Efficient Incorporation of Multiple Latency Targets in the Once-For-All Network

Follow this guide on where everything is located in our project. 

First, run `pip install -r requirements.txt` from the root directory of this project. This should ensure
all your dependencies are present.

Here are the files relevant to our project:
1. ofa/tutorial/evolution_finder.py: This file contains the search with the top-down and the bottom-up
strategies incorporated. The method `run_evolution_search_multi()` corresponds to the bottom-up strategy and 
`run_evolution_search_multi_mixed()` corresponds to the top-down strategy.
2. `topdownexperiments.ipynb`: This is the notebook where you can run and see top-down in action. Please
read the instructions at the top of the notebook!
3. `bottomupexperiments.ipynb`: This is the notebook where you can run and see bottom-up in action. Please
read the instructions at the top of the notebook!
4. `results.ipynb`: This is where we brought together the results of all our experiments and 
visualized them. Please run the code exactly as it is in that file to see the results we obtained.

