# Stance-Classification-Deep-Learning

Stance classification is a subcategory of opinion mining, where the task is to automatically determine whether the author of a piece of text is in favour or against a given target. Automatically detecting stance has widespread applications in information retrieval, text summarization, and textual entailment.


Stance detection is related to, but not the same as sentiment analysis. In sentiment analysis, we are interested in whether a piece of text is positive, negative, or neutral based on just the content of the language used. However, the stance of a piece of text is defined with respect to a target topic, and can be independent of whether positive or negative language was used.
This project is to develop a Deep learning model to classify tweets that are about one of five politically-charged targets: “Atheism”, “the Feminist Movement”, “Climate Change is a Real Concern”, “Legalization of Abortion”, or “Hillary Clinton”. Given the text of a tweet and a target, models must classify the tweet as either FAVOUR or AGAINST, or NEITHER (if the tweet does not express support or opposition to the target topic). The data set, contains a collection of 2,814 training and 1,249 test set tweets. The original dataset is from “Semeval-2016 Task 6: Detecting Stance in Tweets. Saif M. Mohammad et. al. In Proceedings of the International Workshop on Semantic Evaluation (SemEval-16). June 2016.”


Please perform the following steps to run the project code:

  1. Clone the notebook and other data files from the provided GitHub Repository.

  2. From the cloned repository, please upload the “FINAL-CODE.ipynb” file to Google colab environment.

  3. Upload all the data files provided (train.csv, test.csv, independent_dataset.csv) onto your google drive with same names and mount the drive using the code available at the top of notebook. Also, please download the file "glove.twitter.27B.100d.txt" from https://nlp.stanford.edu/projects/glove/ as I have used this pre-trained weight vector. This files also needs to be uploaded on google drive.

  4. Copy the absolute path of files uploaded on the drive. Replace and paste the path in the notebook to the code blocks where the data is being loaded into the notebook.

  5. Connect the Google Colab with GPU runtime. Go to Runtime and click “Run All”

