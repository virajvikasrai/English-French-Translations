# English French Translations
A naive machine translation to translate words from english to french.

## Generate embedidings and transformation matrices
Inputs:
* en_fr : English to French dictionary
* en_embeddings : English to embeddings dictionary
* fr_embeddings : French to embeddings dictionary

Returns:
* Matrix X and matrix Y, where each row in X is the word embedding for an english word, and the same row in Y is the word embedding for the French version of that English word.

## Translation as linear transformation of embeddings
Given dictionaries of English and French word embeddings we will create a transformation matrix R.

## Testing the translation
Hard coding K Nearest Neighbors with cosine similarity as the metric. k-NN is a method which takes a vector as input and finds the other vectors in the dataset that are closest to it.

The 'k' is the number of "nearest neighbors" to find (e.g. k=2 finds the closest two neighbors).

## Computing Accuracy
Translation testing on the unseen data.
