# Approved comments in the Reddit moderation logs
This repository is the data companion for the ICWSM 2021 paper "On Positive Moderation Decisions".

The dataset contains moderator-approved comments on 49 subreddits engaging in an open moderation initiative. The data format is the following:

| field            | description                                                                                                    |
|------------------|----------------------------------------------------------------------------------------------------------------|
| created_utc      | UTC epoch when the comment was approved                                                                        |
| subreddit        | the subreddit where the comment was posted                                                                     |
| target_fullname  | the id of the comment                                                                                          |
| by_automoderator | if the comment was approved by AutoModerator                                                                   |
| by_botmod        | if the comment was approved by any automated moderator,  as identified according to the procedure in the paper |



If you use this dataset, please cite the paper:
```
@inproceedings{samory2021positive,
author = {Samory, Mattia},
booktitle = {Proceedings of the 15th International AAAI Conference on Web and Social Media},
title = {{On Positive Moderation Decisions}},
year = {2021}
}
```



This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
