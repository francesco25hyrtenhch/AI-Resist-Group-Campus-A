# /AI-Resit-Group-Campus-A-YIBS-2025
This repository contains scripts for training an AI model on datasets like Fashion-MNIST. The project covers data preprocessing, model training, and saving the trained model for inference.

## **Part 1: Model Training on Google Colab**  

### **Step 1: Access Model Training Code**  
1. Go to the [`model` folder](https://github.com/francesco25hyrtenhch/AI-Resist-Group-Campus-A/tree/main/model) in our repository
2. Open [ `Ai_Resit_Group_YIBS_2025.ipynb`](https://github.com/francesco25hyrtenhch/AI-Resist-Group-Campus-A/blob/main/Ai_Resit_Group_YIBS_2025.ipynb) 
3. Click the "Open in Colab" button (top-right) 

### **Step 2: Run in Google Colab**  
1. Once opened in Colab, connect to a GPU runtime:
   - `Runtime > Change runtime type > GPU`
2. Run all cells sequentially (`Runtime > Run all`)
3. The notebook will:
   - Install dependencies
   - Download dataset
   - Train model
   - Save `fashion_mnist_cnn_v2.pth`
   - Generate training metrics
   -Generate Loss graph

### **Step 3: Download Trained Model**  
After training completes:
1. Check files panel (left sidebar)
2. Right-click `fashion_mnist_cnn_v2.pth`
3. Select "Download"

![Colab Training Demo](https://colab.research.google.com/drive/1X8aetzvWSKyPKYyDhw4pK-7DXXa5lOZj?usp=sharing)

### **Alternative Manual Setup**  
If you prefer to copy-paste code:
```python
# Clone repository
!git clone https://github.com/francesco25hyrtenhch/AI-Resist-Group-Campus-A.git
%cd AI-Resist-Group-Campus-A/model

# Install dependencies
!pip install torch torchvision matplotlib kagglehub numpy

# Run training script
- Create a new code cell
- Copy the entire content of the `model_training.py` \file  and paste then click run (The play button on the left)