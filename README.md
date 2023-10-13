This Python script, "translate_with_nouns.py," is designed to translate English sentences to Hindi while preserving nouns in their original form. It utilizes the Spacy library for natural language processing and the "translate" library for language translation. The purpose of this script is to provide a customized translation experience where nouns are kept in English, and the rest of the sentence is translated into Hindi.


Prerequisites
1.Python: You need to have Python installed on your system. This script is compatible with both Python 2 and 3.
2.Spacy: Install the Spacy library using pip
3.Translate Library: Install the "translate" library using pip
4.Additionally, download the English language model used for tokenization and part-of-speech tagging:  
          python -m spacy download en_core_web_sm


How it Works
1.The script first loads the English language model from Spacy to perform natural language processing on the input sentences.
2.It identifies nouns in the input sentence based on their part of speech.
3.The script then creates a Translator object to perform the translation into Hindi.
4.If the word "bag" is found in the sentence, it is manually translated and replaced with its Hindi counterpart ("बैग").
5.If no nouns are found in the sentence, each word in the sentence is translated individually using the Translator object. The translated words are then reconstructed into a sentence.
6.The translated sentence is returned.
