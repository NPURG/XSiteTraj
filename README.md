# Dataset format

There are 3 datasets in this Github repository, namely Facebook, Foursquare, and Twitter.
There are multiple files named after the user id in each dataset folder (the sensitive information of the user has been hidden), and the users with the same id in different datasets are matched users.
Each file includes all the trajectories of the corresponding user in the following format:

| header               | description                      |
| -------------------- | -------------------------------- |
| time                 | the timestamp of this trajectory |
| poi                  | the poi of this trajectory       |
| latitude & longitude | latitude and longitude of poi    |


