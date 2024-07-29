# Notes

### [Available Pipelines](https://huggingface.co/transformers/main_classes/pipelines)
* feature-extraction (get the vector representation of a text)
* fill-mask
* ner (named entity recognition)
* question-answering
* sentiment-analysis
* summarization
* text-generation
* translation
* zero-shot-classification

### Zero-Shot Classification
With no training examples.
"don’t need to fine-tune the model on your data to use it. It can directly return probability scores for any list of labels you want!"

Supplied labels, rather than only labels from the model.
Multiple categorical labels, not just positive/negative.
