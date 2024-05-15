# DeepLearningProject

## Drake Lyric Generation

Authors: Dylan Saunders & Owen Anderson

Overview: This project uses deep learning to predict Drake lyrics. We have used Kaggle datasets for both Drake lyrics and lyrics from other
artists' songs. We parsed the dataset, and then used OpenAI's GPT-2 from HuggingFace to tokenize and process the data. After training,
you can then query the new model to generate new Drake lyrics.

How to run: Open the notebook in **Google Colab** and run every cell starting at the top, replacing the HuggingFace token with your own. 
Once you encounter the import error "Using the `Trainer` with `PyTorch` requires `accelerate>=0.21.0`", re-run all cells from the beginning (though
you won't have to redownload the data). After this, you should be all set!

Reproducing the results: As the model is generative, reproducing the _exact_ results is challenging. However, we have included some example 
queries–you can change the input word to match those in the results or tinker with them in any way you see fit. Enjoy testing out what our glorious drake
has to say!


