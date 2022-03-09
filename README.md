The link of the Google Colab notebook is: https://colab.research.google.com/drive/1zY2-YRz-0XTWQGbXo25D1mc5dQMPlqU2?usp=sharing

Points to note:
1. The scraping of comments, cleaning them and assigning them polarity scores has already been done for your convenience. However, code for the same has been provided, but it has been commented out. If required, this code (the first 3 code cells of the Google Colab notebook) can be uncommented and run.
2. An API key would be required to scrape the comments. Since API keys should be kept secure, we cannot share ours. So, the evaluator will have to generate their own.
3. Since we have randomly sampled 25% of our comments from which to train and test our dataset, you may witness slightly different accuracy results than what are mentioned in the report.

Steps to execute:
1. Create a copy of the .ipynb file and do the next steps in your copy of the notebook.
2. A 'polarity-limits.csv' file has been provided by us which is generated after execution of the first 3 code cells. Upload that to the Google Colab notebook if you choose not to run the commented code.
3. The .ipynb file provided has all the necessary code. Just hit 'run all' and you will see the results of all the 3 machine models we have attempted to train.