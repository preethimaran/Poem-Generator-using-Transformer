# Poem-Generator-using-Transformer
In this project I built a poetry generator using a pre-trained gpt-2 transformer that is finetuned on the Poetry foundation dataset.
The code is documented step-by-step in Poetry_generator_using_transformer.ipynb. The same document containes all explanantions and observations too.

## Model  
- **Base model**: GPT-2 (small) from Hugging Face  
- **Framework**: PyTorch + Transformers  
- **Training**: Model was fine-tuned on the poetry dataset.  

## Observations
- The model is not able to learn custom tags like [TITLE], [POEM] amd [TAGS] effectively. Better performance observed when only poems were fed into it.

## Results
-Prompt: the misty forest
-Poem generated:
The misty forest of the sun-flowered moon, a dark and deep one;—where I am not yet but in my youth. This night is all this restful for me: there are no more hours that lie before them so long as they last? No longer must sleep make us weary by itself or with it be left alone to spend these two nights at ease under some tree above their house where you have stayed many years without any other than your own!
"Oh let him come back from his solitude into our room again!" said we on each side till he came out laughing

## Skills Demonstarted
- NLP
- Transformer
- LLM
- Finetuning on custom dataset
- Training and checkpointing
- Text generation pipeline
  

