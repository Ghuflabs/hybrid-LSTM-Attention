# hybrid-LSTM-Attention
![accuracy_curve](https://github.com/user-attachments/assets/66079223-77b4-42de-ab26-a376d50be755)

The rapid advancement of generative artificial intelligence has led to the proliferation of AI-generated texts that are often indistinguishable from human-authored content. Accurately differentiating between these two sources is increasingly critical for various applications, including information integrity, authorship verification, and digital forensics. This paper presents a deep learning-based classification framework that utilizes a Long Short-Term Memory (LSTM) network enhanced with an attention mechanism to effectively identify whether a given text is written by a human or generated by an AI model. To address the issue of class imbalance, the implement method incorporates a positional weighting strategy within the Binary Cross-Entropy with Logits Loss function. The model is trained and validated on a large-scale dataset comprising equal proportions of human-written and AI-generated texts. Experimental evaluations demonstrate that the attention mechanism significantly improves the model's ability to capture meaningful sequence information, leading to highly accurate classification performance. The proposed approach achieves a classification accuracy of 99.91% on the full dataset, indicating its effectiveness in discerning subtle linguistic differences between human and AI-generated texts.
