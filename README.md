# Countdown Numbers Game

## Project Overview

This project develops and analyzes algorithms to solve the Countdown Numbers Game, a segment from the popular TV program "Countdown". The game challenges contestants to reach a random target number using six randomly chosen numbers and basic arithmetic operations. The computational complexity of this game makes it an interesting problem similar to the "subset sum problem", classified as NP-complete in computational theory.

## Computational Background

The game is closely related to the subset sum problem but introduces additional operations which significantly increases its complexity. This project explores two main algorithms:
- **Brute Force Algorithm**: Attempts all combinations of numbers and operations.
- **Backtracking Algorithm**: Applies a more strategic approach to reduce the search space.

Both algorithms find the exact solution under the game's constraints.

## Installation

To run this project, you will need Python. Clone the repository and install the required dependencies:

```bash
git clone https://github.com/rohansikder/ComputationalTheory.git
```

## Usage

### Running the Notebook Locally
1. **Open the Jupyter Notebook:**
   - Ensure you have Jupyter Notebook installed. If not, you can install it via pip:
     ```bash
     pip install notebook
     ```
   - Start Jupyter Notebook by running the following command in your terminal:
     ```bash
     jupyter notebook
     ```
   
2. **Navigate to the Notebook:**
   - A browser window should open automatically. Navigate to the `countdown.ipynb` file within the directory where you cloned the repository and open it.


### [View countdown.ipynb on GitHub](https://github.com/rohansikder/ComputationalTheory/blob/main/countdown.ipynb)
- You can also view the notebook directly in the GitHub repository without running it.
   - Navigate to the `countdown.ipynb` file in the GitHub repository.
   - GitHub will render the notebook with all cells and code displayed


## Implementation Details

 **Random Countdown Game Generator**: Generates a random set of numbers and a target.
  <hr>
<div style="display: flex; justify-content: space-around; align-items: flex-start; flex-wrap: wrap;">
    <div style="text-align: center; padding: 10px;">
        <img src="https://github.com/rohansikder/ComputationalTheory/assets/80963667/21bb9a77-bb92-4326-aa40-7fd7ea895f3e" alt="Countdown Flowchart" width="300">
        <p><strong>Backtracking Solver</strong> Iteratively tests all combinations of numbers and operations.</p>
       <hr>
    </div>
    <div style="text-align: center; padding: 10px;">
        <img src="https://github.com/rohansikder/ComputationalTheory/assets/80963667/5f32efd5-571e-4c29-bd18-8051f547bf5a" alt="Backtracking Flowchart" width="300">
        <p><strong>Backtracking Solver:</strong> Recursively explores potential solutions, using backtracking.</p>
    </div>
</div>





## Performance

The performance of each algorithm is measured in terms of time, efficiency and memory usage.

