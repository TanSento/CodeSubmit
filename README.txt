
COMP6008 - Reinforcement Learning
README for CODE SUBMISSION 


# Declaration of Originality: 
                                 - TanBui_DeclarationOfOriginality.pdf
								 - Jinguo_DeclarationOfOriginality.pdf




# The codes for 6 trained agents are:

- DQN.ipynb             - DQN_ImprovedState.ipynb
- DoubleDQN.ipynb       - DoubleDQN_ImprovedState.ipynb
- DuelingDDQN.ipynb     - DuelingDDQN_ImprovedState.ipynb

Note: - All agents have been trained and saved in their corresponding folder, along with their normalizing scalers (Example: DoubleDQN_128x128)
      - The training can be re-run but will take long times (approximately 2 hours for DQN/DDQN and 4 hours for Duelling-DDQN)
	  - Only need to load the agents and their scalers to test the test sets. The prepared notebooks has thoroughly demonstrate these. Just need to execute the code




# Code for Random Agents: 
                         - RandomAgent.ipynb  Some plots used in the report come from this notebook

# Code for plotting: 
                         - Plot.ipynb         Result plots used in the report are shown in this notebook


# npy folder: store all numpy arrays of the performance of all agents to plot in Plot.ipynb





# csv files: 
				- test_2nd.csv
				- test_3rd.csv
				- test_4th.csv           Each of these csv is the split done for 4-Fold CV
				- train_2nd.csv
				- train_3rd.csv
				- train_4th.csv
				
				- UltimateStocks.csv     All data across 7 years

Note: - There is no separate csv for the 1st Fold because the Train Set simply contains the first 1322 samples and the Test Set contains the last 440 samples.
      - To split, just need to index the array created from UltimateStocks.csv. This has been done in each notebook
	  - For other splits, they are a little more complicated so manual splitting has been done to generate them. 




# Training Results Folder:  - Training Graph Results
												- Double_train
												- DQN_train
												- Duelling_train
							
											

										
										
										  
	




