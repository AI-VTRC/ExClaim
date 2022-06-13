# ExClaim
This dataset is from the paper **ExClaim: Explainable Neural Claim Verification Using Rationalization**.

The datasets are all in Python Pickle format.
```
import pandas as pd
df = pd.read_pickle("./exclaim4000.pkl")
```


## ExClaim Dataset
The ExClaim foundational dataset `exclaim4000.pkl` is the cleaned dataset with 4000+ articles from Politifact as described in the ExClaim paper. It contains the following features:
- Claim
- Verdict
- Evidence
- Ruling



## Raw Dataset
The raw data scraped from Politifact is available as `Politifact3000_Raw.pkl` and it contains the following features:
- Claim
- Politifact URL
- Date
- Source
- Verdict
- Evidence
- Ruling
- Full Article Text



## Citation
If you use this dataset for your research, please cite our paper:

```
@article{ExClaim,
  title={ExClaim: Explainable Neural Claim Verification Using Rationalization},
  author={Gurrapu, Sai and Huang, Lifu and Batarseh, Feras},
  year={2022}
}
```
