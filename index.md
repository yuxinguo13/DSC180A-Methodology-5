## Yuxin Guo ([y5guo@ucsd.edu](mailto:y5guo@ucsd.edu))

Section: *B12*

Mentor: **Gal Mishne** and **Yusu Wang**


## Quarter 2 Project Brainstorming

**What is the most interesting topic covered in your domain this quarter?**

The most interesting topic covered this quarter is the Weisfeiler-Lehman Test, especially its applications in GNN. The WL Test is used for graph isomorphism testing, which can efficiently determine whether two graphs are structurally identical. In GNN, the WL test aggregates and updates node features by considering the features of neighboring nodes, effectively capturing the local graph structure. If the WL test told us that two graph is the same, then we cannot run GNN on these two graphs, since no matter what model we applied to the two grpahs, they will always give us the same result.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

A potential investigation is to develop a new GNN model that effectively capture the long-range dependency in graph data, like the data we used for our quarter one's project, the IMBD and the Cora dataset. This project would focus on integrating transformer, like attention mechanisms within GNN. The primary goal is to address the limitations of existing GNNs when dealing with large-scale graphs. The investigation could start by analyzing the core components in currect GNN models, and how they manage long-range interactions. Or the investigation would involve experimenting with different positional encoding strategies to help GNNs better understand the structure of the graph. 

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

A significant modification that could be beneficial is the multi-scale feature extraction. This change could design a network that can aggregate and process information from various graph scales and the features of its neighborhood nodes. The motivation is to enable the model to capture a more comprehensive range of the graph features, from immediate neighbors to more further nodes, thereby addressing the challenge of long-range interactions more effectively. And also this change could benefit from dynamic neighborhood sampling techniques, where the size and composition of the neighborhoods are adjusted during the training process based on the model's learning process. This adaptability could provide a more complete understanding of graph structures and improve the model's performance on large-scale graphs.

**What other techniques would you be interested in using in your project?**

(Your answer here)

