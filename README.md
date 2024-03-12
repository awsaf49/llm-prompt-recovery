# LLM Prompt Recovery with [KerasNLP](https://github.com/keras-team/keras-nlp) and [Keras](https://github.com/keras-team/keras)

<div align="center">
    <img src="https://i.ibb.co/8xZNc32/Gemma.png">
</div>

In this competition, the goal is to find the prompt used to transform a given text. Specifically, we're seeking the prompt or instruction used in the [Gemma 7B-it](https://www.kaggle.com/models/google/gemma/frameworks/pyTorch/variations/7b-it-quant) model to convert one text to another. Typically, large language models are instructed to transform one text to another style, but here we're tasked with the inverse: finding the instruction/prompt used for the transformation. This notebook walks you through fine-tuning the **Gemma 2b-it** model with LoRA for this prompt recovery task using KerasNLP. Witih KerasNLP, we can fine-tune with LoRA using just a few lines of code.

**Fun fact**: This notebook is backend-agnostic, supporting TensorFlow, PyTorch, and JAX. However, the best performance can be achieved with `JAX`. KerasNLP and Keras enable the choice of preferred backend. Explore further details on [Keras](https://keras.io/keras_3/).

**Note**: Code is available at [kaggle](https://www.kaggle.com/code/awsaf49/prompt-recovery-with-gemma-kerasnlp-starter/).
