# Wordcloud-Reddit-comments

The purpose of this repository is to help the users get an idea of what has been discussed on a Reddit submission. This 
is obtained via a Wordcloud based on all the comments from a given Reddit URL. 

Additionally, the function will summarize the text if requested.


The first part consists of importing relevant libraries and loading personal details related to the Reddit dev account.

In the second part, the user will find the function that generates a word cloud from Reddit submission's comments obtained 
through a Praw technique. The URL is assigned via an input function. Therefore, please have the URL in the clipboard to 
be pasted in the relevant input box. Finally, a plot will be shown with the word cloud based on the summary of all the Reddit comments.

The summary parameter has to be set to False to disable it. 

