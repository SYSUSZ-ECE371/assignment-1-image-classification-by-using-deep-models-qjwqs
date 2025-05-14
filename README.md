# ECE371 Assignment 1: Flower Classification with Deep Models

**Course**: ECE371 Neural Networks and Deep Learning  
**Due Date**: 23:59, 14th May 2025  
**Weight**: 15% of Final Grade  

---

## 📝 Assignment Overview  
This assignment focuses on training deep learning models for flower classification. It includes two exercises:  
1. **Exercise 1**: Fine-tuning a pre-trained model using MMClassification.  
2. **Exercise 2**: Completing a PyTorch training script for flower classification.  

---

## 📂 Repository Structure  

---

## 🛠️ Setup & Usage  

### Exercise 1: MMClassification Fine-Tuning  
1. **Prepare Dataset**  
   - Unzip `flower_dataset.zip` and organize into ImageNet format:  
     - Split into `train` (80%) and `val` (20%) folders.  
     - Generate `classes.txt`, `train.txt`, and `val.txt` (see example in assignment PDF).  
2. **Modify Configuration**  
   - Update `config.py` to:  
     - Set `num_classes=5`.  
     - Adjust data paths and learning rate (e.g., `lr=0.001`, `epochs=10`).  
     - Link to pre-trained model from [MMClassification Model Zoo](https://github.com/open-mmlab/mmpretrain/tree/1.x).  
3. **Run Training**  
   ```bash
   python tools/train.py config.py --work_dir=Ex1/

   
---

**Good Luck! 🌼**
