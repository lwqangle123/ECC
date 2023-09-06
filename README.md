# ECC
error correcting codes to defense adversarial attacks on GNN
Please download all files especially the deeprobust toolbox;
K_bound is matlab m file for determing the minimum K that satisfies all conditions in paper;
Figure is a matlab m file containing all codes for reproducing all experimental figures, along with fig_5_a to fig_10_b which are matlab .mat data files for each figure.
Two example files are provided to show the defense performance of our ECC method, where we test three attacks (random attack, dice attack, topology attack) on GCN and GAT. (We just showcase the examples with specific parameter settings, and users can modify them like K, tau, hyper-paremeters for GNN to meet their own goals.)
Our method can be applied to any GNN models. Regarding Point-GNN for object detection, please refer to Point-GNN (https://github.com/WeijingShi/Point-GNN) for how to construct graphs and train the model. After that, our defense method can be tested against three attacks on Point-GNN. 
