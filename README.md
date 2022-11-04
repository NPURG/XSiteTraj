# dataset format

There are 3 datasets in this GitHub repository: Facebook, Foursquare, and Twitter. There are multiple files named after the user id in each dataset folder (the sensitive information of the user has been hidden), and the users with the same id in different datasets are matched users. 

Each file includes all the trajectories of the corresponding user in the following format:

| column name               | description                      |
| -------------------- | -------------------------------- |
| time                 | the timestamp of this trajectory point |
| poi                  | the poi of this trajectory point       |
| longitude & latitude | longitude and latitude of the poi    |

# cite us

```bibtex
@article{LI20211,
  title    = {Matching user accounts with spatio-temporal awareness across social networks},
  journal  = {Information Sciences},
  volume   = {570},
  pages    = {1-15},
  year     = {2021},
  issn     = {0020-0255},
  doi      = {https://doi.org/10.1016/j.ins.2021.04.030},
  url      = {https://www.sciencedirect.com/science/article/pii/S0020025521003571},
  author   = {Yongjun Li and Wenli Ji and Xing Gao and Yao Deng and Wei Dong and Dongxu Li},
  keywords = {User identification, Spatio-temporal awareness, Match user accounts, Check-in data, User trajectory},
  abstract = {User identification aims at matching user accounts across social sites, which benefits many real-world applications. Existing works based on user trajectories usually address spatial and temporal data separately while not fully utilizing the coupling relation between them. Differently, in this work, we jointly consider spatialtemporal information in users’ acitvities to improve the user identification method. In particular, we observe that check-in records of different users tend to create inconsistent spatialtemporal information. These inconsistencies are useful for eliminating false user matching. Inspired by this observation, we propose a novel user identification method that captures the correlation of spatial and temporal information and the inconsistency in check-in records. It contains three main steps. 1) We measure the similarity of users’ trajectories based on a kernel density estimation, which considers spatial and temporal information simultaneously. 2) We assign a weight to each check-in record to favor discriminative ones. 3) We utilize the inconsistency among check-in records to compute penalties for trajectory similarity. The pair of accounts with higher similarity (than a predefined threshold) is then considered to be from the same user. We evaluate our approach on three ground-truth datasets. The results show that the proposed method offers competitive performance, with F1 values reaching 86.12%, 85.08% and 78.34%, which demonstrates the superiority of the proposed method over state-of-the-art methods.}
}

@article{9738836,
  author  = {He, Wenqiang and Li, Yongjun and Zhang, Yinyin and Li, Xiangyu},
  journal = {IEEE Transactions on Computational Social Systems},
  title   = {A Binary-Search-Based Locality-Sensitive Hashing Method for Cross-Site User Identification},
  year    = {2022},
  volume  = {},
  number  = {},
  pages   = {1-12},
  doi     = {10.1109/TCSS.2022.3158664}
}

```
