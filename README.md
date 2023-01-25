# nlp-dataset-expander
a demo for a system to expand nlp datasets by rephrasing them


!!! do not expand same dataset twice !!!
this will cause the data to become extremly low quality


each expansion doubles the dataset's size by rephrasing each sentence.
currently works only on txt files, does not support your special formatting.


use like so:

txt file:

I am so excited for the weekend!
This is the best news I've heard all day.
I am incredibly grateful for your support.
I can't believe how beautiful this sunset is.
I am so sad about the loss of my loved one.
I am so tired of being taken advantage of.
I am so stressed out by all the work I have to do.
I am so let down by the lack of support from my friends.

expanded will be:
4 original positive sentences
4 original negative sentences
4 expanded (rephrased) positive sentences
4 expanded (rephrased) negative sentences
