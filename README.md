# Implementing-FX-Graph-Mode-Post-Training-Static-Quantization
Implementing FX Mode Graph Post training Static Quantinzation on a Resnet18 model

This project demonstrates the effectiveness of post-training static quantization on a ResNet-18 model using the CIFAR-10 dataset.

Key features include:  
- **Final Layer Modification:** The last layer of ResNet-18 was adjusted to 10 classes to better suit the CIFAR-10 dataset.  
- **Early Stopping:** Implemented to prevent overfitting and optimize training time.  
- **Quantization and Model Conversion:** The model was quantized and converted to CPU as FX Graph Mode quantization is not supported on GPUs.  
- **Model Size Comparison:** The original model size of 42.72 MB was reduced to 10.70 MB after quantization, showcasing significant memory efficiency.  
- **Accuracy:** The quantized model achieved an accuracy of **78.53%** on the CIFAR-10 test set.

# Results
**Original Model:** 42.72 MB
**Quantized ModelSize:** 10.70 MB
**Test Accuracy:** 78.53%


