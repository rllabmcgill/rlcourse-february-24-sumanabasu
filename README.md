# TD(0) or Monte Carlo : Which makes the more efficient use of limited data?
## Sumana Basu (260727568)

To find which one of TD(0) or MC converges faster than the other, I have compared the performance of both the algorithms in two different environments -
  * Wall Following Domain
  * GridWorld Domain

Experiment :
* Generated 50,000 episodes for each of the environments
* Calculated the expected value function using TD(0)
* Based on 4000 episodes iterated for 100 times, searched for optimal hyper parameter alpha (learning rate) for each of the algorithms
* Compared performance of TD(0) and MC for best choice of learning rates

Observation :
* For Wall Following domain, MC is as good as TD(0)
* For GridWorld domain, TD(0) converges faster than MC

Conclusion:
Out of these two prediction algorithms, which method learns faster or which one makes the more efficient use of limited data is dependant on the environment and choice of policy
