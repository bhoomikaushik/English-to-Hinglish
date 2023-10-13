


Prerequisites
1.Python
2.Spacy
3.Translate Library

model- python -m spacy download en_core_web_sm






How it Works
1.The script first loads the English language model from Spacy to perform natural language processing on the input sentences.
2.It identifies nouns in the input sentence based on their part of speech.
3.The script then creates a Translator object to perform the translation into Hindi.
4.If the word "bag" is found in the sentence, it is manually translated and replaced with its Hindi counterpart ("बैग").
5.If no nouns are found in the sentence, each word in the sentence is translated individually using the Translator object. The translated words are then reconstructed into a sentence.
6.The translated sentence is returned.
