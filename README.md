# RSGPT: A Generative Transformer Foundation Model Pre-trained on Ten Billion Data for Retrosynthesis Planning


Available retrosynthesis data are limited to only millions. Therefore, we pioneering utilized the RDChiral reverse synthesis template extraction algorithm to generate chemical reaction data. This method precisely aligns an existing template’s reaction center with those of synthons, yielding a complete reaction. Consequently, **over 10 billion high-quality** reaction data entries were generated. A generative pretrained transformer (GPT) foundation model called RSGPT was subsequently developed for template-free retrosynthesis planning, by pre-training using the 10 billion generated reaction data. Inspired by the strategies of LLMs, we introduced reinforcement learning from AI feedback to capture the relationships among products, reactants, and templates more accurately. Extensive experiments demonstrate that our model achieves state-of-the-art performance on the USPTO-50K dataset, with a Top-1 accuracy of **63.4%**, substantially outperforming previous models. To the best of our knowledge, RSGPT is the pioneering GPT foundation model for retrosynthesis planning, providing groundbreaking insights and potential scalability across a wide range of chemical scenarios and applications.

## Installation

Instructions on how to install and set up the project.

```bash
# Clone the repository
git clone https://github.com/Zhao-Xinda/RSGPT.git

# Navigate to the project directory
cd yourproject

# Install dependencies
conda env create -f environment.yml
```

## Inference Codes
https://github.com/Zhao-Xinda/RSGPT/tree/v1.0.0

## Data and model weights
```
RSGPT_weight
Link:  https://pan.baidu.com/s/1W0KZv8LyilJ0U66u7OT-Yw?pwd=qlg3 
Extraction Code：qlg3

USPTO_data
Link：https://pan.baidu.com/s/1Zu4I1oen1zIHrma3PMFlJA?pwd=6ljh 
Extraction Code：6ljh 
```


