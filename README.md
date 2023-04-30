# Text Summarization using NLTK and heapq

This project aims to summarize large articles into shorter summaries using natural language processing techniques. The NLTK library is used for tokenization and stopwords removal, and the heapq module is used for extracting the most important sentences.

## How to use
1. Install the required packages mentioned in `requirements.txt` using `pip`.
2. Run the `text_summarization.py` script and enter the path of the article file.
3. The summarized output will be displayed on the console.

## Limitations
The summarization process heavily depends on the quality and length of the input article. The summary may not always capture the essence of the entire article, and may omit important information.

## Future work
In future, the project can be extended to handle multiple articles and generate a summary based on the common topics present in them. Additionally, techniques such as TextRank and GPT-3 can be explored for better summarization.
