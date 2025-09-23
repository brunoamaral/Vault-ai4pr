---
kind: Definition
contexts:
tags:
aliases:
  - fine-tuning
folder: Definitions
---
# Fine Tuning


## Definition
É o processo de ajustar um modelo de IA, que foi treinado com uma grande quantidade de informação, para tarefas ou contextos específicos. 

## Description
Podemos considerar a criação inicial de um LLM como sendo *pré-treino*, porque estamos a recorrer a uma grande quantidade de informação para que possa responder a questões usando modelos de probabilidade.

O *fine-tuning* é a fase depois desse treino em que afinamos a capacidade do modelo para responder a pedidos de uma categoria específica.

Está relacionado com o conceito de *transfer learning* e não sei a diferença entre os dois.

## Examples
Treinar um LLM open-source para responder a perguntas sobre ensaios clínicos. [@nabaisUsingLargeLanguage2025](@nabaisUsingLargeLanguage2025.md)


> - **Customizing style**: Models can be fine-tuned to reflect a brand’s desired tone, from implementing complex behavioral patterns and idiosyncratic illustration styles to simple modifications like beginning each exchange with a polite salutation.
>     
> - **Specialization**: The general linguistic abilities of LLMs can be honed for specific tasks. For example, Meta’s Llama 2 models were released as base foundation models, chatbot-tuned variants (Llama-2-chat) and code-tuned variants (Code Llama). 
>     
> - **Adding domain-specific knowledge**: While LLMs are pre-trained on a massive corpus of data, they are not omniscient. Using additional training samples to supplement the base model’s knowledge is particularly relevant in legal, financial or medical settings, which typically entail use of specialized, esoteric vocabulary that may not have been sufficiently represented in pre-training.
>     
> - **Few-shot learning**: Models that already have strong generalized knowledge can often be fine-tuned for more specific classification texts using comparatively few demonstrative examples. 
>     
> - **Addressing edge cases**: You may want your model to handle certain situations that are unlikely to have been covered in pre-training in a specific way. Fine-tuning a model on labeled examples of such situations is an effective way to ensure they are dealt with appropriately.
>     
> - **Incorporating proprietary data**: Your company may have its own proprietary data pipeline, highly relevant to your specific use case. Fine-tuning allows this knowledge to be incorporated into the model without having to train it from scratch.


## Sources
- [What is Fine-Tuning?](What%20is%20Fine-Tuning?.md)

