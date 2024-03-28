# Abstractive Text Summarization Tools using Transformers

## Using GPT-3.5, BART, and T-5 Transformers

We created a summarization tool using three different transformers to evaluate how well each one of these transformers does. We find that there's a trade-off in using each of these transformers when we fine-tuned or prompt engineer them.

## FIne-tuning BART, T-5 and prompt engineering GPT-3.5 model:

In order to fine-tune our models, we used the cnn and daily news article datasets (100). The articles were extracted via API because we did not want to waste storage. The evaluations for each will be explored!

## Book summarization comparison

We also explored how well our models worked for a chapter summarization of a book (we fine-tuned the best news summarization model, to summarize a chapter of a book). We then compared and evaluated the summarization with a Cliff Notes summarization, to see how closely aligned our summarization was, compared to a professional summarization.

## Web Scraper

Along with the summarization, we also incorporated the aspect of using a web scraper to get extract text from web sites and then summarizing this texts (we tried for news articles in specific).