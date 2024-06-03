# COMP6008 - Reinforcement Learning

This repository contains the code submission for the COMP6008 - Reinforcement Learning course.

## Declaration of Originality

- TanBui_DeclarationOfOriginality.pdf
- Jinguo_DeclarationOfOriginality.pdf

## Trained Agents

The codes for the 6 trained agents are:

- `DQN.ipynb`
- `DQN_ImprovedState.ipynb`
- `DoubleDQN.ipynb`
- `DoubleDQN_ImprovedState.ipynb`
- `DuelingDDQN.ipynb`
- `DuelingDDQN_ImprovedState.ipynb`

**Note:**
- All agents have been trained and saved in their corresponding folders, along with their normalizing scalers (Example: `DoubleDQN_128x128`).
- The training can be re-run but will take a long time (approximately 2 hours for DQN/DDQN and 4 hours for Duelling-DDQN).
- To test the agents on the test sets, you only need to load the agents and their scalers. The prepared notebooks thoroughly demonstrate this. Simply execute the code.

## Random Agents

The code for random agents is in `RandomAgent.ipynb`. Some plots used in the report come from this notebook.

## Plotting

The code for plotting is in `Plot.ipynb`. Result plots used in the report are shown in this notebook.

## Data

### NPY Folder

The `npy` folder stores all numpy arrays of the performance of all agents, which are used for plotting in `Plot.ipynb`.

### CSV Files

- `test_2nd.csv`
- `test_3rd.csv`
- `test_4th.csv`
- `train_2nd.csv`
- `train_3rd.csv`
- `train_4th.csv`
- `UltimateStocks.csv` (All data across 7 years)

Each of these CSV files represents a split done for 4-Fold Cross-Validation.

**Note:**
- There is no separate CSV file for the 1st Fold because the Train Set simply contains the first 1322 samples, and the Test Set contains the last 440 samples.
- To split the data, you just need to index the array created from `UltimateStocks.csv`. This has been done in each notebook.
- For other splits, they are a little more complicated, so manual splitting has been done to generate them.

## Training Results

The training results and graphs can be found in the following folders:

- `Training Graph Results`
- `Double_train`
- `DQN_train`
- `Duelling_train`