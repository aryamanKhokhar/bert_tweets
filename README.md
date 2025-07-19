# BERT-Toxic-Tweet-Classification

**Classification of toxic tweets using a fine-tuned BERT transformer in PyTorch.**

This project showcases a complete workflow to build a robust toxic content detector using BERT, covering:

- **Data preprocessing:** Text cleaning, tokenization, and encoding for BERT input  
- **Label mapping & dataset splitting:** Stratified train/validation/test splits  
- **Custom Dataset:** Efficient data batching with a PyTorch `Dataset` class  
- **Model design:** BERT backbone with dropout and a classification head  
- **Training:** Fine-tuning with AdamW optimizer and learning rate scheduling  
- **Evaluation:** Metrics tracking, loss visualization, and confusion matrix analysis  
- **Inference:** Making predictions on new tweets with class probabilities  
- **Model persistence:** Saving and loading the trained model for future use  

Ideal for intermediate PyTorch users looking to apply transformers to real-world NLP moderation tasks — easily adaptable to other toxicity detection or text classification problems.
