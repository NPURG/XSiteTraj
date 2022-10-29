# dataset format

There are 3 datasets in this GitHub repository: Facebook, Foursquare, and Twitter. There are multiple files named after the user id in each dataset folder (the sensitive information of the user has been hidden), and the users with the same id in different datasets are matched users. 

Each file includes all the trajectories of the corresponding user in the following format:

| column name               | description                      |
| -------------------- | -------------------------------- |
| time                 | the timestamp of this trajectory point |
| poi                  | the poi of this trajectory point       |
| longitude & latitude | longitude and latitude of the poi    |
