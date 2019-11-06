# Neutral evolution and turnover over centuries of English word popularity

Python code to reproduce main results in the Advances in Complex Systems paper, "Neutral evolution and turnover over centuries of English word popularity" 

**Python2 code (not Python3)**

If you make us of this code, please cite: Ruck D.J., Bentley R.A., Acerbi A., Garnett P. and Hruschka D.J. (2017). Role of neutral evolution in word turnover during centuries of English Word popularity. Advances in Complex Systems,20(6).

## Raw Data

Raw Google 1gram data can be downlaoded from http://storage.googleapis.com/books/ngrams/books/datasetsv2.html

## Scripts

Run "FNM.py" for the full sample neutral model. This initiates the neutral model where the full population of traits is retained at each time step 

Run "PNM.py" for the partial sample neutral model. This initiates the neutral model where an exponentially increasing random sample of the full population is retained at each time step.

Run "downloadNgrams.py" to create yearly word counts between 1700 and 2000 from raw Google 1-gram data

Run "Ngrams_summary.py" to derive summary statistics (power law, heaps law, turnover profile) from yearly 1-gram word counts 

Run "genetic.py" to use genetic algorithms to fit the partial sampling neutral model (PNM) to the summary statistics of the Google 1-gram data.
