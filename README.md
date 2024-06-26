# Torque-based visual reacher with RL
<p align="center">
  <img src="https://github.com/amir-noohian/torque-visual-reacher-rl/blob/main/docs/Franka-VisualReacher.gif" alt="animated" />
</p>
This repository is for the task of torque-based visual reacher with reinforcement learning. 

## Supported Algorithms
- Soft Actor Critic (SAC)

## Installation instructions
1. Install miniconda or anaconda
2. Create a virtual environment:
```bash
conda create --name myenv python=3.6    # Python 3.6 is necessary
conda activate myenv
```
3. Install packages with:
```bash
pip install -r requirements.txt
pip install .
```

## Run experiment
```python
 python3 task_franka_visual_reacher_dense_torque.py  --work_dir "./results" --mode 'l' --seed 0 --env_steps 200100 
```

## Contributors
- Amir Noohian

## Acknowledgments
I would like to express our gratitude to Prof. Martin Jagersand for his advice and guidance throughout the development of this project.
