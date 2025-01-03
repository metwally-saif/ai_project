# AI Project Overview

## Project Structure

ai_project                                        
├─ data                                           
│  ├─ medical_images                              
│  │  |_ raw                                      
│  │      |_ all_images                            
│  └─ sentiment_analysis                          
│     ├─ processed                                
│     │  ├─ tokenizer.json                        
│     │  ├─ X_test.npy                            
│     │  ├─ X_train.npy                           
│     │  ├─ X_val.npy                             
│     │  ├─ y_test.npy                            
│     │  ├─ y_train.npy                           
│     │  └─ y_val.npy                             
│     └─ raw                                      
│        └─ sentiment_data.csv                    
├─ models                                         
│  ├─ medical_image_classification                
│  │  └─ class_indices.json                                                  
│  └─ sentiment_analysis                          
│     ├─ history1.npy                             
│     └─ history2.npy                                            
├─ notebooks                                      
│  ├─ medical_image_classification                
│  │  ├─ 1_data_exploration.ipynb                 
│  │  ├─ 2_data_preparation_medical_images.ipynb  
│  │  ├─ 3_model_training.ipynb                   
│  │  ├─ 4_model_evaluation.ipynb                 
│  │  └─ 5_summary_and_reflection.ipynb           
│  └─ sentiment_analysis                          
│     ├─ 1_data_exploration.ipynb                 
│     ├─ 2_data_preparation.ipynb                 
│     ├─ 3_model_training.ipynb                   
│     ├─ 4_model_evaluation.ipynb                 
│     └─ 5_summary_and_reflection.ipynb           
├─ reports                                        
│  ├─ medical_image_classification                
│  │  ├─ model1_classification_report.txt         
│  │  └─ model2_classification_report.txt         
│  ├─ sentiment_analysis                          
│  │  ├─ sentiment_model1_report.txt              
│  │  └─ sentiment_model2_report.txt              
│  └─ final_report.ipynb                          
├─ README.md                                      
└─ requirements.txt                               

## Getting Started
1. Download the medical image dataset from [this link](https://huggingface.co/datasets/hf-vision/chest-xray-pneumonia)
2. Place the downloaded images in `data/medical_images/raw/all_images/`
3. make sure that the images names match the format image_{number}.jpg
4. make sure that the `image_labels.csv` file matches the downloaded data
 

## Notebooks
**1_DATA_EXPLORATION** - Reviews raw datasets  
**2_DATA_PREPARATION** - Cleans and preprocesses data, including medical images  
**3_MODEL_TRAINING** - Builds and trains models (CNN, LSTM, etc.)  
**4_MODEL_EVALUATION** - Evaluates models using accuracy, F1-score, etc.  
**5_SUMMARY_AND_REFLECTION** - Summarizes insights and next steps  

## Setup
1. Clone repository  
2. Install dependencies using requirements.txt  
3. Run Jupyter notebooks in sequence  
