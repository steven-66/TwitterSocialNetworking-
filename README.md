
This assignment will allow you to do a more open-ended exploration of online social networking. The goal is to let you use some of the tools we've learned in class on your own. This project is to be done individually. There are several requirements to constrain your work, defined below.

The main goals are to:
1. **Collect** raw data from some online social networking site (Twitter, Facebook, Reddit, Instagram, etc.)
2. Perform **community detection** to cluster users into communities.
3. Perform **supervised classification** to annotate messages and/or users according to some criterion.
4. Analyze the results and **summarize** your conclusions.


- `collect.py`: This should collect data used in your analysis. This may mean submitting queries to Twitter or Facebook API, or scraping webpages. The data should be raw and come directly from the original source -- that is, you may not use data that others have already collected and processed for you (e.g., you may not use [SNAP](http://snap.stanford.edu/data/index.html) datasets). Running this script should create a file or files containing the data that you need for the subsequent phases of analysis.
- `cluster.py`: This should read the data collected in the previous step and use any community detection algorithm to cluster users into communities. You may write any files you need to save the results.
- `classify.py`: This should classify your data along any dimension of your choosing (e.g., sentiment, gender, spam, etc.). You may write any files you need to save the results. This method should used supervised learning, which means you may have a secondary file containing any labeled data for the problem.
- `summarize.py`: This should read the output of the previous methods to write a textfile called `summary.txt` containing the following entries:
  - Number of users collected:
  - Number of messages collected:
  - Number of communities discovered:
  - Average number of users per community:
  - Number of instances per class found:
  - One example from each class:

