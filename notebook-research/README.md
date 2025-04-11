# Notebook Projects

## `Custom_Quantum_Self_Attention_Transformer_on_Dynex.ipynb`
This project is a customization of the quantum self-attention transformer on Dynex from the Medium article titled [How to Implement a Quantum Self-Attention Transformer on Dynex](https://medium.com/@dynexcoin/how-to-implement-a-quantum-self-attention-transformer-on-dynex-4c3c72e03eea). The customizations made are as follows:

1. Replaced 'BasisEmbedding' with 'AngleEmbedding'.
2. Modified the quantum circuit to allow the use of vector weights.
3. Added several additional functions to support sentence generation.
4. Includes model training to update the model weights.

## `QPT.ipynb`
This project attempts to apply a Quantum Neural Network (QNN) layer as a hidden layer in GPT-2. However, this QNN is not yet trainable, requiring further research to make the QNN trainable along with GPT-2.

## `QT5.ipynb`
Similar to the `QPT.ipynb` project, this project focuses on applying the `Custom_Quantum_Self_Attention_Transformer_on_Dynex.ipynb` to the T5-small language model. However, it is still not trainable and requires further handling. Unlike the `Custom_Quantum_Self_Attention_Transformer_on_Dynex.ipynb` project, this one includes an additional AttentionPooling for dynamic feature reduction to the output dimension according to the number of configured qubits.
