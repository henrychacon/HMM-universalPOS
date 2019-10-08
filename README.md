# Universal part-of-speech tagset and HMM applied to The Cat in the Hat

## Objective:
To implement from scratch a Hidden Markov model using as hidden variables the set of universal tags proposed by Petrov, Das, and McDonald in their paper *A universal Part-of-Speech Tagset*, [Link](https://github.com/slavpetrov/universal-pos-tags)

The python package *nltk* was used to tokenize each word from the book: **The Cat in the Hat** by Dr. Seuss. Then, for each token is assigned a tag from the PennTree Bank found in the library nltk.

The correspondence between Universal tags and PennTree tags is implemented. Then, the Markov Chain model is produced considering as observed states the words from the original text and the hidden model, the tags.

## Input files:
1. A text file, in this case: The Cat in the Hat, **drseuss.txt** from [Link](https://github.com/robertsdionne/rwet/blob/master/hw2/drseuss.txt)
2. A tag mapping between The PennTree bank and the Universal POS [Link](https://github.com/slavpetrov/universal-pos-tags)

## Output:
The Hidden Markov model considering as hidden model the set of universal tags and observed or emitted set words from the book
