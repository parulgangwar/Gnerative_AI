# Apply Lightweight Fine-Tuning to a Foundation Model

As a part of Generative Artifcial Intelligence Nanodegree program by Udacity, this is my first project on "Apply Lightweight Fine-Tuning to a Foundation Model" Lightweight fine-tuning is one of the most important techniques for adapting foundation models, because it allows is to modify foundation models for 
our needs without needing substantial computational resources.

Parameter-efficient fine-tuning is a technique to use pre-trained machine learning models with minimal additional data or computational resources. Basically in this technique, we use specific parameters rather than retraining the entire model. This approach, often used in transfer learning, accelerates convergence and enhances generalization, particularly in NLP, computer vision, and related fields.

In this project, I've applied parameter-efficient fine-tuning using the Hugging Face peft library. In order to do, I've followed following steps.

Step 1: Load a Pre-trained Model and Evaluate Its Performance
I have used thee "distilbert-base-uncased" model from Hugging Face peft library. I  have used the subset of Amazon Polarity dataset. As entire dataset was quite heavy.
In this step, I have prepared the dataset and have evaluated the pre-trained model's performance on the validation dataset.

Step 2: Perform Parameter-Efficient Fine-Tuning Using the Pre-trained Model
In this step, I've defined training arguments for fine-tuning and have also Fine-tuned the pre-trained model on the training subset.
I've also saved the fine-tuned model.

Step 3: Perform Inference Using the Fine-Tuned Model and Compare Its Performance to the Original Model
In this step, I've loaded the fine-tuned model and have evaluated the fine-tuned model's performance on the validation dataset.
I've also compared the trainer evaluation results with the final fine-tuned evaluation results.

### Installations

* scikit-learn
* torch 
* transformers 
* datasets 

### Apply Lightweight Fine-Tuning to a Foundation Model at Github
[Github Link for Project](https://github.com/parulgangwar/Gnerative_AI)

