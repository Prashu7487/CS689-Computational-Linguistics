Along with this 'README.md' The submitted folder '231110036-Assignment2.zip' contains-
finetunedBERT_ner_model :finetuned IndicBERT model
finetunedINDIC_ner_model :finetuned IndicNER model
231110036-assignment2-IndicBERT_finetuning.ipynb :question 2 part 1(finetuning IndicNER)
231110036-assignment2-IndicNER_finetuning.ipynb  :question 2 part 2(finetuning IndicBERT)
231110036-assignment2_problem4.ipynb             :question 4 comparison
231110036-Assignment2-question5.pdf              :question 5 report
ChatGPT_ner_file.txt  : for Question 3, ner labels predicted by ChatGPT (text formatted for processing)
ChatGPT_raw_ner_file.txt  :same as above, this is actual text prediction by ChatGPT
manual_ner_file.txt  :NER labels done manually for my 25 sentences at 'https://bangla.iitk.ac.in/cs689' 
raw_sentences_file.txt  :sentence assigned to me for manual classification

for running notebooks dependencies should be installed (mentioned in each notebook) and all required data should be in current directory, also resulted file/folders will be saved in current directory.
dependencies installation commands:
pip install transformers
pip install torch
pip install datasets
pip install scikit-learn

All files are independent to run (dataset/files mentioned should be in current directory) except notebook for question 4 that requires dumped models to be present in current directory...and these will be genereted after executing files for question 2.

NOTE: Dataset is loaded online, no need to download the dataset to run these files.
