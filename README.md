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
@article{fu2023xsitetraj,
  title={XSiteTraj: A Cross-site User Trajectory Dataset},
  author={Fu, Jiazheng and Li, Yongjun},
  journal={Data in Brief},
  pages={109783},
  year={2023},
  publisher={Elsevier}
}

@article{zhang2023trajectory,
  title={A Trajectory-Based User Movement Pattern Similarity Measure for User Identification},
  author={Zhang, Yinyin and Li, Yongjun and Ji, Wenli},
  journal={IEEE Transactions on Network Science and Engineering},
  year={2023},
  publisher={IEEE}
}

```
