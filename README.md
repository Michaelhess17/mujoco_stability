# MuJoCo Stability Analysis for Animal Locomotion

This repository contains code to run reinforcement learning (RL) algorithms on MuJoCo simulations, aimed at matching animal locomotor data. The primary goal is to study the stability profiles of the learned algorithms for individual animals.

## Overview

This project uses MuJoCo physics engine and reinforcement learning techniques to:
1. Simulate animal locomotion
2. Train RL agents to match real animal locomotor data
3. Analyze the stability of the learned locomotion patterns

## Requirements

- Python 3.7+
- MuJoCo 2.0+
- OpenAI Gym
- PyTorch
- NumPy
- Matplotlib

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/Mujoco_stability.git
   cd Mujoco_stability
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Install MuJoCo following the official instructions: [MuJoCo Installation Guide](https://mujoco.org/download)

## Usage

1. Prepare your animal locomotor data in the `data/` directory.

2. Configure the simulation parameters in `config.yaml`.

3. Run the main script:
   ```
   python main.py
   ```

4. Analyze the results using the provided Jupyter notebooks in the `analysis/` directory.

## Project Structure

- `src/`: Source code for RL algorithms and MuJoCo simulations
- `data/`: Directory for storing animal locomotor data
- `models/`: Trained model checkpoints
- `analysis/`: Jupyter notebooks for data analysis and visualization
- `config.yaml`: Configuration file for simulation parameters

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [MuJoCo](https://mujoco.org/)
- [OpenAI Gym](https://gym.openai.com/)
- [PyTorch](https://pytorch.org/)
