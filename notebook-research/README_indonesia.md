# Notebook Projects

## `Custom_Quantum_Self_Attention_Transformer_on_Dynex.ipynb`
projek ini adalah projek kustomaisasi dari quantum self attention transformer pada Dynex dari artikel medium yang berjudul [ How to Implement a Quantum Self-Attention Transformer on Dynex ](https://medium.com/@dynexcoin/how-to-implement-a-quantum-self-attention-transformer-on-dynex-4c3c72e03eea) Kustomisasi yang dilakukan adalah sebagai berikut

1. Mengganti 'BasisEmbedding' menjadi 'AngleEmbedding'
2. Mengubah sirkuit kuantum, agar bisa menggunakan vector weight
3. menambahkan beberapa fungsi tambahan untuk mendukung generate sentence
4. terdapat training model untuk update bobot model

## `QPT.ipynb`
projek ini mengupayakan untuk menerapkan Quantum Neural Network layer sebagai hidden layer pada GPT2. Namun QNN ini masih belum bisa trainable, sehingga butuh research lebih lanjut lagi untuk membuat QNN ini trainable beserta dengan GPT2

## `QT5.ipynb`
sama seperti poin `QPT.ipynb`, projek ini berfokus pada menerapkan projek `Custom_Quantum_Self_Attention_Transformer_on_Dynex.ipynb` pada projek model bahasa T5-small namun masih belum trainable dan masih membutuhkan penanganan lebih lanjut lagi. berbeda seperti `Custom_Quantum_Self_Attention_Transformer_on_Dynex.ipynb`, pada projek ini terdapat tambahan AttentionPooling untuk reduksi fitur dinamis menjadi dimensi output sesuai dengan jumlah qubit yang di konfigurasi. 