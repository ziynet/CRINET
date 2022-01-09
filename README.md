# CRINET (CeRna Interaction NETwork)
CRINET: A computational tool to infer genome-wide competing endogenous RNA (ceRNA) interactions and groups

To learn more about Crinet, read our paper at: https://journals.plos.org/plosone/article/authors?id=10.1371/journal.pone.0251399

![SUPREME pipeline](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0251399)
## Description of files
- **crinet.R**: The script that runs Crinet on sample dataset with 10 cores.  
  - To use your own datasets, comment **line 5** and load your own data.  
  - To convert sample-specific hyperparameters to the default one, use **line 11** instead of **line 13** (or modify hyperparameters by yourself).  
  - Update number of core (the variable ```core.no```) on **line 8** accordingly.
  
- **CRINET_sample.rda**: Supplemental file including sample datasets used in Crinet.  
- **crinet.functions.R**: Supplemental file including function declarations used by Crinet  

