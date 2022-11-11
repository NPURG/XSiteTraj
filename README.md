# dataset format

There are 3 datasets in this GitHub repository: Facebook, Foursquare, and Twitter. There are multiple files named after the user id in each dataset folder (the sensitive information of the user has been hidden), and the users with the same id in different datasets are identical users. 

Each file includes all the trajectories of the corresponding user in the following format:

| column name               | description                      |
| -------------------- | -------------------------------- |
| time                 | the timestamp of this trajectory point |
| poi                  | the poi of this trajectory point       |
| longitude & latitude | longitude and latitude of the poi    |

# cite us

If you use the datasets above, please cite our work.

```bibtex
@article{LI20211,
  title    = {Matching user accounts with spatio-temporal awareness across social networks},
  journal  = {Information Sciences},
  volume   = {570},
  pages    = {1-15},
  year     = {2021},
  issn     = {0020-0255},
  doi      = {https://doi.org/10.1016/j.ins.2021.04.030},
  author   = {Yongjun Li and Wenli Ji and Xing Gao and Yao Deng and Wei Dong and Dongxu Li},
  keywords = {User identification, Spatio-temporal awareness, Match user accounts, Check-in data, User trajectory},
}

@article{9738836,
  author  = {He, Wenqiang and Li, Yongjun and Zhang, Yinyin and Li, Xiangyu},
  journal = {IEEE Transactions on Computational Social Systems},
  title   = {A Binary-Search-Based Locality-Sensitive Hashing Method for Cross-Site User Identification},
  year    = {2022},
  pages   = {1-12},
  doi     = {10.1109/TCSS.2022.3158664}
}

```
