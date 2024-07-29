---
title: "Progress"
permalink: /docs/progress/
excerpt: "Haitao's current Progress. First frontend project using jekyll package"
last_modified_at: 2024-07-28T16:22:24-06:00
redirect_from:
  - /theme-setup/
toc: true
---

This site is developed base on [Gem-based theme](http://jekyllrb.com/docs/themes/) as a pratice base, which is currently depolyed on GitHub Page.

## Neural Machie Transclation Study:

For a normal LLM project, it always include several piplines: Data preprocess pipeline. Modeling Inference Pipeline. Post-inference pipeline.

### Seq2seq Model:

The seq2seq model uses LSTMs for both encoding and decoding, allowing variable-length sequences to be mapped to fixed-length memory, which encodes sentence meaning. However, the seq2seq model faces limitations with long sequences due to the fixed memory size, known as the information bottleneck. To address this, the concept of attention is introduced, allowing the model to focus on important words at each time step, improving translation accuracy for longer sequences. 

[^seq2seq]: The seq2seq model was developed by Google in 2014

**Concept of Attention:**  Allows the model to focus on specific parts of the input when making predictions.
{: .notice--info}

### Attention for Seq2seq Model:

Attention was introduced to improve seq2seq models for translating longer sentences. The traditional seq2seq models struggle with long sequences because they must store the entire input sequence in a single vector. Attention addresses this by assigning weights to different parts of the input, allowing the model to focus on important words. This improves performance, as shown by higher BLEU scores in models using attention compared to traditional seq2seq models. 

**How attention works:** The attention works by calculating alignment scores and converting them into weights using a feedforward neural network and the softmax function, producing a context vector that emphasizes important words for the decoder.
{: .notice--warning}

---

The study site is still under development.