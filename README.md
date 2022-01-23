# CRINET (CeRna Interaction NETwork)
CRINET: A computational tool to infer genome-wide competing endogenous RNA (ceRNA) interactions and groups

To learn more about Crinet, read our paper at: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0251399

For any questions/issues about CRINET, please feel free to comment/discuss at [https://ziynetnesibe.com/crinet](https://ziynetnesibe.com/crinet)

 <img src="https://ziynetnesibe.com/wp-content/uploads/2021/08/journal.pone_.0251399.g001-768x610.png" width="550" height="450" />

 <!-- ![SUPREME pipeline](https://storage.googleapis.com/plos-corpus-prod/10.1371/journal.pone.0251399/1/pone.0251399.g001.PNG_L?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=wombat-sa%40plos-prod.iam.gserviceaccount.com%2F20220109%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20220109T041427Z&X-Goog-Expires=86400&X-Goog-SignedHeaders=host&X-Goog-Signature=2a084a572773124c0ca8c74e87533eea7c9de54c98e8e907309e47556215da222f58851bb2f468658a7400cb652864f09f1dd0fb5c277793151121c124a47164b78c54bdf8c09ef942dc9b98976dc328ae9520ad23b8eff604aa43ec3eadcb4ba321146dbb7298f7b0f2cf441b8d60848d124d6b0dcc539a4c96191c41ac76907da0267685a30542159a77e265762e9e4be86e14596b5c7c1ed2636fab3509e829c83d11e032fae956bd4fe479ad7f3a5949406636a0048343d25fe45d34ca3d3392d2e3c2ac90c3b8155618c657d72896798f8a044e8112810958f39fde2192194b0dbc26c7ec16a113c1cbfb17ff177bbbe70f6b33df29ffd83610f2460693)  -->

## Description of files
- **crinet.R**: The script that runs Crinet on sample dataset with 10 cores.  
  - To use your own datasets, comment **line 5** and load your own data.  
  - To convert sample-specific hyperparameters to the default one, use **line 11** instead of **line 13** (or modify hyperparameters by yourself).  
  - Update number of core (the variable ```core.no```) on **line 8** accordingly.
  
- **crinet_sample.rda**: Supplemental file including sample datasets used in Crinet.  
- **crinet.functions.R**: Supplemental file including function declarations used by Crinet  

