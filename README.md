# Cerebellum Inspired Surprise Detection

![image](https://github.com/user-attachments/assets/33c9f2a9-bc52-4fa3-9c37-00abf2740293)

The Spiking Neural Network (SNN) architecture proposed above performs unsupervised learning-based pattern recognition for MNIST images.

In this proposed surprise detection model, we've utilized an approach that leverages short-term and long-term plasticity mechanisms to regulate excitatory and inhibitory conductance in response to 2D MNIST images. This allows for the identification of surprise detection based on the output potential of Purkinje cells. As an example, the model is trained to recognize label zero images as normal, and when a label one image is introduced, changes in excitatory and inhibitory conductances cause the Purkinje cell firing to pause, indicating surprise. With continuous input of label one images, the model adapts to perceive them as normal, leading to the resumption of Purkinje cell firing. Example test case as below.

![image](https://github.com/user-attachments/assets/27f5b2eb-b8d0-46a1-935e-52e40534062b)

# code

To see the results, first, you need to prepare spike sets using: MNIST_SurpriseDetection_SpikeSetPrep.ipynb

Then you can do the simulation with: MNIST_SurpriseDetection_Simulation.ipynb

# Results
three test benches
- Normal 0 : Anomaly 1
- Normal 0 : Anomaly 1to9
- Normal 1to9 : Anomaly 0

For 100 Monte Carlo runs per random test sequence, we can see an average accuracy variation below.

![image](https://github.com/user-attachments/assets/a4d3e88c-d45c-4081-b851-2ba5b649a8bf)

