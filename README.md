# 2048_RL_Project
Final project for Reinforcement learning class - Automate 2048 Game

Team Members:
- Jyoti Prakash Maheshwari
- Prakhar Agrawal

This github repo includes code for the 2048 RL project, where the objective was to train an RL agent to play 2048. To learn more about this project, please check out the final report [here](https://github.com/jyotipmahes/2048_RL_Project/blob/master/2048_final_report.pdf).

In order to try a demo of the model on your computer, clone the repo and type the following command on the terminal:

```
python demo.py
```

This will give you a demo where the agent uses a random policy.

If you want to see a demo of our best model, i.e., Monte-Carlo Tree Search, type the following command:

```
python demo.py --mode best --steps <n_steps>
```

Where n_steps is the number of steps for wnich the model looks ahead while deciding its action.
