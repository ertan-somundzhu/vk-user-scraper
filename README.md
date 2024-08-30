This is my another pet project. It scrapes data and friends lists of number of users 

This code returns several files:
  1. 2 Excel files with all the publicly availible information of:
       a. Initial 10000 users (turned out to be around 3000), randomly selected by generating their id's
       b. 25 (or less) friends of each user from the random 10000 batch
  2. 2 processed Excel files mentioned earlier, several columns were added and unpacked
  3. An Excel files with links of users to one another via friendships for a graph
  4. A Gexf files that contains a graph of users
Note: attached files are not the original files, names, nicknmaes, etc. were hashed

Libraries used: requests, pandas, numpy, json, random, time, tqdm, collections, networkx

Approximate runtime - 6-ish hours for 25-ish thosand users

Another note: to run this code you have to get VK's token for API
