# quantization
**🧠 MNIST Dataset Quantization with Keras**

This project demonstrates the application of Deep Learning Model Optimization techniques such as Pruning and Quantization on the popular MNIST handwritten digits dataset. Built using TensorFlow/Keras, it showcases how to achieve significant model compression while maintaining (or even improving) performance, with detailed benchmarking of accuracy, model size, and inference speed.

**📁 Project Structure**


Quantization.ipynb: Main Jupyter notebook containing:

Baseline model training on MNIST

Post-training quantization (PQT)

Quantization-aware training (QAT)

Model evaluation and comparison

**🚀 Techniques Covered**

✅ Baseline model development and training

✅ Post-training quantization to INT8 (PQT)

✅ Quantization-aware training (QAT) for better accuracy under quantization constraints

✅ Model size, latency, and load time comparisons

✅ Accuracy and loss evaluation across different compression techniques

**📊 Sample Results**

Model Type	File Size	Loss	Accuracy	Load Time (s)

Baseline Model	522 KB	0.1653	95.31%	0.0897

PQT Compressed + Quantized	45 KB	0.0903	97.31%	0.0359

QAT Quantized Model	92 KB	0.9505	74.49%	0.0006


⚡ Key Takeaways
Quantization dramatically reduces model size and improves loading speed.

Post-training quantization can achieve excellent accuracy with minimal additional training effort.
Quantization-aware training allows for even finer control during training to mitigate accuracy loss due to quantization.

These techniques are critical for deploying deep learning models on edge devices or resource-constrained environments.

**🔗 References:**

Keras Model Optimization Documentation:  https://www.tensorflow.org/model_optimization

Netron - Visualize ML Models :https://netron.app/
