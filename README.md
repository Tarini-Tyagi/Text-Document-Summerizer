# Text-Document-Summerizer
Text Summarizer will helps in summarizing the text. We can upload our data and as output we’ll get the summary of that data.
The project is mainly a text summarizer using Natural Language Processing concepts. The main purpose is to provide reliable summaries of provided document. The unnecessary sentences will be discarded to obtain the most important sentences.
# Why we need automatic text summarization?
Summaries reduce reading time.
When researching documents, summaries make the selection process easier.
Automatic summarization algorithms are less biased than human summarizers.
Personalized summaries are useful in question-answering systems as they provide personalized information.
Using automatic or semi-automatic summarization systems enables commercial abstract services to increase the number of texts they are able to process.
# Text Summarization Approaches
# Extractive Summarization: 
These methods rely on extracting several parts, such as phrases and sentences, from a piece of text and stack them together to create a summary.  

# Abstractive Summarization:
These methods use advanced NLP techniques to generate an entirely new summary. Some parts of this summary may not even appear in the original text. 

# Tools and Techniques used
Python3

NLTK Library

Anaconda Navigator

# Methodology to be followed
The 6 steps implementation

1. Load text document
After loading the text document it will be divided into paragraphs and further those paragraphs will be divided into sentences.
2. Text Pre-processing 
Create the word frequency table:
First create a dictionary for the word frequency table from the text.
For this, we should only use the words that are not part of the stopWords array.
We’re applying this method on the text_string, which could be anything like a news article, a book page or an email.

3. Tokenize the sentences
Split the text_string in a set of sentences. For this, we will use the inbuilt method from the nltk
sent_tokenize(text_string)

4. Score the sentences: Term frequency
We’re using the Term Frequency method to score each sentence.
Score a sentence by its words, adding the frequency of every non-stop word in a sentence.

5. Find the threshold
Here, we are considering the average score of the sentences as a threshold. You can use other methods to calculate the threshold. One of the method can be Text Rank Algorithm.

6. Generate the summary
Select a sentence for a summarization if the sentence score is more than the average score.




