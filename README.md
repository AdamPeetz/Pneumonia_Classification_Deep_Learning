# Detecting Viral and Bacterial Pneumonia from Chest Xrays

### With Colaboratory, Drive, Transfer Learning, and Data Augmentation

#### Summary
Pneumonia is a lung infection that can be caused by a virus or bacteria growing in the lungs. A common way to screen for pneumonia is to analyze chest x-rays for signs of the infection. On an x-ray, pneumonia will present itself as little white dots in the lungs called infiltrates. This distinct visual feature of pneumonia makes it a candidate for detection by convolutional neural networks. If a visual difference exists between normal lungs and infected lungs, then it should be detectable by a convolutional neural network.   <br>

#### Methods
This notebook creates a three-class model that classifies x-rays as either normal, having bacterial pneumonia, or viral pneumonia. It is designed to use free cloud computing resources from Google. Collaboratory is used for coding and computing, and Drive is used to host input data for the model. Presenting a free and generalized approach to this problem creates a foundation that can be applied to any deep learning problem with the modification of a few lines of code. <br>

To solve the problem, this notebook will employ data augmentation and transfer learning. These two techniques are known to improve classification scores on small datasets. 
