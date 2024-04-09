# Baseline Submission for a Re-Ranker in the 1st International Workshop on Open Web Search #wows2024

This is a classification model that predicts a document is generated by an LLM if it contains the word "delve".

You can run it directly via (please install `tira` via `pip3 install tira`, Docker, and Python >= 3.7 on your machine): 

```
tira-run \
	--input-dataset nlpbuw-fsu-sose-24/authorship-verification-validation-20240408-training \
	--image fschlatt/authorship-verification-trivial:0.0.1
```