# SI630 Course Project (Tourist Destination Introduction Generation Language Model from Tourist Reviews based on Fine-tuned Flan-T5)
For more detail, please look at the [Project Report](SI630_Project_Report_leczhang.pdf).

## Abstract
The project builds a generative language model which can automatically generate the introduction of tourist destinations based on the reviews from tourists. The model uses the sentence transformer and TextRank algorithm to find and pick up important sentences, and then used finetuned Flan-T5 model with appropriate prompts to encode and decode into an objective, highly generalized introduction. The research verified that TextRank is effective in extracting representative information from complicated data. It also verified that appropriate prompts can significantly improve the performance of seq2seq pretrained model. Our final model in this project research has 37.537 Rouge1 score, which is 240 times higher than the baseline. It verified that pretrained seq2seq models are feasible and promising for complicated text generation tasks.

## Required Packages
* Python 3.9
* Pandas, Numpy, tqdm, sklearn
* PyTorch 2.0.0
* nltk 3.8.1
* datasets 2.12.0
* Transformers 4.28.1
