# Text-Summarization_-TensorFlow-
ِAmazon reviews Summarization_ using MT5 Model With Huggingface platform

Although there already exist various fine-tuned models for summarization on the Hugging Face Hub, almost all of these are only suitable for English documents. So, to add a twist in this section, we’ll train a bilingual model for English and Spanish.

As we’ll see, these summaries are concise because they’re learned from the titles that customers provide in their product reviews.

We’ll use the Multilingual Amazon Reviews Corpus to create our bilingual summarizer. This corpus consists of Amazon product reviews in six languages and is typically used to benchmark multilingual classifiers. However, since each review is accompanied by a short title, we can use the titles as the target summaries for our model to learn from! 

![Alt text](https://github.com/Yasser-shrief/Text-Summarization_-TensorFlow-/blob/main/Models.JPG)
