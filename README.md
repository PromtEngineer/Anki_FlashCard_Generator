# Anki Card Generator from PDF Files

This repo will generate Flash cards that you can use in Anki for learning. 

# Environment Setup
In order to set your environment up to run the code here, first install all requirements:

```shell
pip install -r requirements.txt
```

## Generate Flash Cards. 

Simply put your PDF files in the `SOURCE_DOCUMENTS` folder. 

Run the following command to process your data.

```shell
python Anki_flashcards_creator.py
```

It will generated a flashcards.txt file that you can import into Anki. 

#### Things to Remember. 
This will divide your files into smaller chunks. Sometimes because of the nature of the prompt and LLMs, you will not get the exact format that you ask it for. You might have to play around with the prompt or write a small script to put it in the proper format. 