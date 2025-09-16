# Poem-Generator-using-Transformer
In this project I built a poetry generator using a pre-trained gpt-2 transformer that is finetuned on the Poetry foundation dataset.
The code is documented step-by-step in Poetry_generator_using_transformer.ipynb. The same document containes all explanantions and observations too.

## Model  
- **Base model**: GPT-2 (small) from Hugging Face  
- **Framework**: PyTorch + Transformers  
- **Training**: Model was fine-tuned on the poetry dataset.  

## Observations
- The model is not able to learn custom tags like [TITLE], [POEM] amd [TAGS] effectively. Better performance observed when only poems were fed into it
  

