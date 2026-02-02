- https://aws.amazon.com/blogs/machine-learning/an-introduction-to-preparing-your-own-dataset-for-llm-training/
	- This just talks about how to prepare the data for training.
- https://www.heavybit.com/library/article/train-LLM-on-own-data
	- This actually has a guide with code and how to train the model with code examples

[Natural Language Processing Text Classification Models On Hugging Face](https://huggingface.co/models?pipeline_tag=text-classification&num_parameters=min:0,max:9B&sort=trending)

- [A model that's already trained to determine educational content](https://huggingface.co/HuggingFaceFW/fineweb-edu-classifier)
	- I tested this model and the output was kind of weird. The score was only 1.8 for a behavioral science video

[Video on training an LLM](https://www.youtube.com/watch?v=9Ge0sMm65jo)

Use **Google Colab** to train if Macbook/Mac Mini aren't enough.

- Need to parse out the timestamps in the video using Python
- Remove stopwords and tokenize the data using ChromaDB