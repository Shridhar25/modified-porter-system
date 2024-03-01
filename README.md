Enhancement in Stemmer Design: Natural Language Semantics Perspective

Natural Language Processing is the sub-field of artificial intelligence that is used to analyse and synthetize human language. It makes effective use of stemming algorithms (stemmer) which is used to perform the morphological breakdown of various inflected and derivational words of English language. It reduces a word to its base/root form also known as the stem. It is most widely used to enhance the efficiency of information retrieval system, word analysis, indexing, and text mining applications. The Porters stemmer is conventionally used for removing these common morphological and inflectional endings (suffix) from the words in English language. It uses a set of pre-defined rules that are less complex when compared to other existing stemmers.
However, the downside of this algorithm is increased ambiguity, a result of over-stemming or under-stemming.
The two identified errors in stemming process are: 
1. Over-stemming
2. Under-stemming

In the domain of information retrieval, vector of words are used in different sense, for example: Connect,
Connection, Connections, Connecting, Connected. Upon presenting the vector of words to the stemmer, it is
expected to get the final word as: Connect. But if the same rule is applied on different set of words like:
Relations, Relating: then the expected word is “Relate”. This is not possible in the Porter Stemmer.
The major drawbacks of the Porter Stemmer are: 
1. The Stemming process is rule based and fixed.
2. The Stemming process is not based on the context of word within the sentence.
3. The Stemming process does not take into consideration, the phonetics of word and its resultant
outcome after stemming.
4. The Stemmer does not guarantee the true sense of word resulting after stemming process.

This project proposes solutions to remove and invalidate identified several imprecisions that are encountered during the stemming process.
