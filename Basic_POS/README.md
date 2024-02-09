# Part-of-Speech Tagger using NLTK
This repository contains a simple implementation of a Part-of-Speech (POS) tagger using the Natural Language Toolkit (NLTK) library in Python. The tagger is trained on labeled data and can be further trained with additional manually labeled training data.

## The code consists of two main sections:

## Training the Initial Model:

- The initial model is trained using a small labeled dataset (labeled_data).
Default tags are specified for words not present in the training data.
Additional Training with Manually Labeled Data:

- More training data (training_data) can be manually provided to improve the model's accuracy.
The model is re-trained with the new data, utilizing the UnigramTagger with a backoff to the DefaultTagger.

# Training the Initial Model
default_tagger = DefaultTagger('NN')
tagger = UnigramTagger(train=labeled_data, backoff=default_tagger)

# Evaluating with a new sentence
new_sentence = ["I", "enjoy", "working", "with", "natural", "language", "models", "."]
predicted_tags = tagger.tag(new_sentence)
print(predicted_tags)

# Additional Training with Manually Labeled Data
default_tagger = DefaultTagger('NN')
tagger = UnigramTagger(train=training_data, backoff=default_tagger)

# Re-evaluating with the same new sentence
predicted_tags = tagger.tag(new_sentence)
print(predicted_tags)

## Additional Notes
Feel free to experiment with different training datasets and evaluate the tagger's performance on various types of text.

This implementation uses a simple UnigramTagger with a DefaultTagger backoff. You can explore other NLTK taggers and backoff strategies based on your specific use case and data.

Ensure that your training data is representative of the language patterns you expect the tagger to handle.
