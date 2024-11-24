# HealthAlignSumm-Utilizing-Alignment-for-Multimodal-Summarization-of-Code-Mixed-Healthcare-Dialogues
This GitHub repo will contain the dataset and  the proposed model in the paper HealthAlignSumm}: Utilizing Alignment for Multimodal Summarization of Code-Mixed Healthcare Dialogues that got accepted in EMNLP 2024 Findings 

# Update-24/11/2024

The dataset used in the paper is present in the Data folder. (It is to be noted we used the dataset present in the work  https://github.com/NLP-RL/MM-CliConSummation/tree/main . We have converted it to Hindi-English codemixed using the prompt mentioned in the paper)
The proposed model and a few of the baselines is present in the code folder.

# To run HealthAlignSumm:

First need to train the HealthSumm model using: CUDA_VISIBLE_DEVICES= xxx python HealthSumm.py

Then using the saved model, you need to run: CUDA_VISIBLE_DEVICES= xxx python HealthAlignSummSumm.py

To generate the final summaries: CUDA_VISIBLE_DEVICES= xxx python dpoinference.py 


