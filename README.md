# Cerebellum

![image](https://github.com/user-attachments/assets/33c9f2a9-bc52-4fa3-9c37-00abf2740293)

The Spiking Neural Network (SNN) architecture proposed above performs unsupervised learning-based pattern recognition for MNIST images.

In this proposed surprise detection model, we've utilized an approach that leverages short-term and long-term plasticity mechanisms to regulate excitatory and inhibitory conductance in response to 2D MNIST images. This allows for the identification of surprise detection based on the output potential of Purkinje cells. As an example, the model is trained to recognize label zero images as normal, and when a label one image is introduced, changes in excitatory and inhibitory conductances cause the Purkinje cell firing to pause, indicating surprise. With continuous input of label one images, the model adapts to perceive them as normal, leading to the resumption of Purkinje cell firing. Example test case as below.

![image](https://github.com/user-attachments/assets/27f5b2eb-b8d0-46a1-935e-52e40534062b)
