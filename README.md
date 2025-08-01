# Cerebellum Inspired Neural Network for Novelty Detection

The Spiking Neural Network (SNN) architecture proposed here performs unsupervised learning-based pattern recognition for MNIST images.

In this proposed novelty detection model, we've utilized an approach that leverages short-term and long-term plasticity mechanisms to regulate excitatory and inhibitory conductance in response to 2D MNIST images. This allows for the identification of novel/anomalous detection based on the output potential of Purkinje cells. As an example, the model is trained to recognize label zero images as normal, and when a label one image is introduced, changes in excitatory and inhibitory conductances cause the Purkinje cell firing to pause, indicating detection. With continuous input of labeled one images, the model adapts to perceive them as normal, leading to the resumption of Purkinje cell firing. Example test case is below.

<img width="468" height="632" alt="image" src="https://github.com/user-attachments/assets/a52e2893-3306-468c-b51e-0239c5707c0b" />


# code

To see the results, first, you need to prepare spike sets using: MNIST_SurpriseDetection_SpikeSetPrep.ipynb

Then you can do the simulation with: MNIST_SurpriseDetection_Simulation.ipynb


