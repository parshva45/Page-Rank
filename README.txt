- The three tasks of the IR HW2 are performed by:

1) One python file page_rank.py (the one that needs to be run)
(Task 2)

2) A directory named "Logs" having the following text files:

- bfs_crawler_log which contains a list of 1000 pages obtained
from running BFS crawler

- dfs_crawler_log which contains a list of 1000 pages obtained
from running DFS crawler

- sample.txt which contains a sample graph

- G1.txt which contains graph obtained from running BFS crawler
(Task 1)

- G2.txt which contains graph obtained from running DFS crawler
(Task 1)

- sample_statistics.txt which contains statistics over sample

- G1_statistics.txt which contains statistics over G1
(Task 1)

- G2_statistics.txt which contains statistics over G1
(Task 1)

- perplexity_log.txt which contains perplexity values obtained
in each round until convergence for sample, G1, G2
(Task 2)

- Top_50_in_sample.txt which contains top 50 pages in sample in
terms of the final PageRank score

- Top_50_in_G1.txt which contains top 50 pages in G1 in
terms of the final PageRank score
(Task 2)

- Top_50_in_G2.txt which contains top 50 pages in G2 in
terms of the final PageRank score
(Task 2)

- Task3_speculation.txt which contains comparison and speculation
between top 10 pages by link-counts and by PageRank for G1 and G2
(Task 3)


Setup :

- You should have a Python programming environment set up on your machine.


Run the code:

- Run from your Terminal or Comand Prompt.
  Go to to the directory where page_rank.py resides and use the command
  > python page_rank.py sample G1 G2
  to run.

(Here sample, G1, G2 are graphs which are passed as command line arguments)

Results:

The results are generated in "Logs" directory
