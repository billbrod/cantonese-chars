# README

To load in, use the following (in Python):

```
data = pd.read_table('data/survey-data.txt',encoding='utf-8',header=1,sep='\t',index_col=False)
key = pd.read_table('data/survey-key.txt',encoding='utf-8',header=2,sep='\t',index_col=False)
```
