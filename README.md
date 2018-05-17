enron dataset

preparation for research
1. low data
2. corpus
3. relational dataset(it's dataset)

you can give access to prepared enron dataset for research in enrondata.org(this website include FERC/Aspen, CALO, USC, CMU Intermedate, CMU, UMass and Queens University).


=====

low data to mongo db

http://soloso.blogspot.jp/2011/07/getting-enron-mail-database-into.html

bson 2 json
- bow_insert.py
- date_insert.py
- tofrom_insert.py

json 2 corpus
- gensim format
  - corpus xxx.mm
  - dictionary xxx.dict
  - model xxx.tfidf, etc

corpus 2 relational dataset
- pandas
  - Normalize xxx.txt
  - label namelist.txt
