# Reinforcement Learning Project (PhD course)
### Massimiliano Nigro, Luca Subitoni

This repository contains the [code](https://github.com/lucasubitoni/Reinforcement_Learning_Project_PhD_course/blob/main/main.ipynb) and the [final report](https://github.com/lucasubitoni/Reinforcement_Learning_Project_PhD_course/blob/main/Report.pdf) relative to the "reproducibility challenge" project of the Reinforcement Learning PhD course offered by Politecnico di Milano.

The selected paper for the project is: [Generative Adversarial Imitation Learning](https://arxiv.org/abs/1606.03476) by Jonathan Ho and Stefano Ermon.

[Politecnico di Milano - Reinforcement Learning course information](https://www11.ceda.polimi.it/manifestidott/manifestidott/controller/MainPublic.do?EVN_DETTAGLIOINSEGNAMENTO=EVENTO&c_insegn=061642&aa=2023&k_corso_la=1380)

<hr>

#### CODE DESCRIPTION:
The code ("main.ipynb") is meant to work on Google Colab (last check: 28th June 2024). 
The setup of the Jupyter Notebook is subdivided in the following sections:

- <b>Install packages</b>: it installs the necessary packages (including MuJoCo) and loads the RL_project folder (which you can download from this GitHub repository) from your Google Drive account. A script from the imitation Python library is corrected

- <b>General functions</b>: definition of Python functions useful throughout the code

The main code is then subdivided in the following sections:

1. <b>Creating the environment for both the expert policy and the imitation algorithms</b>: creations of the environments (must run)
2. <b>Train the expert algorithm</b>: uses TRPO to train an expert policy and a random policy (optional, if you already have run this, it can be skipped! Load the previous results in the Google Colab file manager and go to number 3.)
3. <b>Imitation learning</b>: defines the imitation learning algorithm implemented, i.e., Behavioral Cloning and GAIL. (must run)
4. <b>Compare the GAIL and Behavioral Cloning to the expert</b>: train and compare the imitation algorithms to the expert and the random policy (must run)
5. <b>Plot curves to visualize the comparison</b>: generates the normalized curves present in the GAIL paper. If you already have the .csv results, you can directly load them in the Google Colab file manager

<hr>

#### Example of Expert Agent trained using TRPO:

https://github.com/user-attachments/assets/86ef7d24-f440-4703-bb07-6c145e5f873d


