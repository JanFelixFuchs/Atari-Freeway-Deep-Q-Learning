# Projekt-Seminar Deep Learing

## Topic: Deep Reinforcement Learning (Atari Freeway)

### Explanation: Projekt-Seminar

During the third semester of my computer science studies, I worked on this project together with three fellow students as part of the Projekt-Seminar “Deep Learning”. The Projekt-Seminar is a semester-long event, scheduled by my university, during which scientific work is practised. Under the supervision of a professor, we worked together on the topic of deep reinforcement learning. We researched on different approaches, built artificial intelligences based on self built neural networks in order to run the Atari game Freeway and evaluated our results.

<img src="./Freeway%20gif/freeway.gif" align="right"/>

### Group division:

Since we were four people, we divided our group into the following two subgroups. For privacy reasons the names of the fellow students have been removed:

1. Subgroup: Member 1
2. Subgroup: Member 2, Member 3 and Jan Felix Fuchs

Although two subgroups of two people each, would have seemed more obvious, we have choosen this constellation in agreement with our professor since our first member already had some experience on artificial intelligence and neural networks whereas the rest of the group has not worked on this topic yet.

### Approach and target:

After a short introduction phase during which we got more familiar with the topic deep learning, we started our group work. The subgroups focused on two different approaches of deep reinforcement learning pursued the goal of building an artificial intelligence which performs as succesfull as possible at the Atari game Freeway. While team member 1 worked on the model-based approach ME-TRPO, we tried out the model-free approach Deep Q-Learning. For reasons of evaluability, the subgroup consisting out of three members split up after the half of the semester and worked individually. As a result the finished project consisted out of the following parts:

- Notebook of member 1 (Subgroup 1)
- Notebook of member 2
- Notebook of member 3
- Notebook of Jan Felix Fuchs

During a final presentation we presented the results of our two subgroups and compared them with each other.

### Structure of this repository:

Again, due to privacy reasons, this reposity does not contain our whole group work. The notebook contained in this repository only includes the results of the group work of the second subgroup as well as the individual work of Jan Felix Fuchs. In total the repository includes the following files:

- **_Notebook:_**
  This folder contains the Notebook which contains the group work (second subgroup) on the model-free approach as well as the individual work of Jan Felix Fuchs
- **_Diagrams DQN:_**
  This folder contains the diagrams which were created during the training processes of the DQN (part of the group work)
- **_Diagrams CNN:_**
  This folder contains the diagrams which were created during the training process of the CNN (part of the individual work)
- **_Trained Models DQN:_**
  This folder contains the trained DQN models which were created during the training processes of the DQN (part of the group work)
- **_Trained Models CNN:_**
  This folder contains the trained CNN models which were created during the training processes of the CNN (part of the individual work)
- **_README.md_**

Files which were created by the other students are not included in this repository. Additional information can be found inside the notebook.

### Working environment:

In order to set up the development environment we used the python distribution Anaconda.
Therefore we installed the following modules. A short comprehension to each module can be found inside the notebook.

- pip install gym[atari]
- pip install ale_py
- pip install autorom[accept-rom-license]
- pip install torch
- conda install pytorch-cuda = 11.6
