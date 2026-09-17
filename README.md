
# Backpropagation in Artificial Neural Network (ANN)

This repository contains a step-by-step Excel calculation of **Backpropagation in an Artificial Neural Network (ANN)**.

The Excel workbook is created as a practical reference to help understand how a neural network calculates its output, measures the error, propagates the error backward, calculates gradients, and updates the weights.

## 🧠 Neural Network Architecture

The example uses a simple neural network with:

- **2 Input Neurons:** X1, X2
- **2 Hidden Neurons:** H1, H2
- **1 Output Neuron:** O1
- **6 Weights:** W1, W2, W3, W4, W5, W6
- **Activation Function:** Sigmoid
- **Learning Rate:** 0.1
- **Target Output:** 1.0

### Network Structure

```text
        Hidden Layer
       
X1 ─────► H1 ─────►
  \       │          \
   \      │           ► O1
    \     │          /
     ► H2 ─────────►
X2
