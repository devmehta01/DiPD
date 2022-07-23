# [DiPD (Disruptive Event Prediction Dataset)](https://arxiv.org/abs/2111.15629)
Riots and protests, if gone out of control, can cause havoc in a country. We have seen examples of this, suchas the BLM movement, climate strikes, etc., which caused worldwide disruption. Our motive behind creatingthis dataset was to use it to develop machine learning systems that can give its users insight into the trendingevents going on and alert them about the events that could lead to disruption in the nation. If any event startsgoing out of control, it can be handled and mitigated by monitoring these events before the matter escalates.This dataset collects tweets of past or ongoing events known to have caused disruption and labels these tweets as 1.

### Motivation:
Machine Learning researchers can benefit from this dataset, while Governmental and Securityagencies can also benefit from the machine learning models resulting from this dataset.Government organizations can use this on future tweets to keep track of events and mitigatethem before they become violent

### Description:
The data is extracted from from Twitter . The dataset consists of instances which are categorised into event and non-event category. The file contains 4 csv files two of which are unprocessed tweets from event and non-event category and the other two are preprocessed tweets from the same two categories

The tweets have following attributes- created_at,retweet_count,followers_count,location , username, statuses_count, label

The dataset can be retrieved from the [Drive link](https://drive.google.com/drive/folders/1hFvG6Gzr3bcUxblKb3wpOfO1acBwMyDk?usp=sharing) given. Kindly cite us if you use this dataset.

[Link to the paper](https://arxiv.org/abs/2111.15629)

You can cite using-
```
@misc{soni2021dipd,
      title={DiPD: Disruptive event Prediction Dataset from Twitter}, 
      author={Sanskar Soni and Dev Mehta and Vinush Vishwanath and Aditi Seetha and Satyendra Singh Chouhan},
      year={2021},
      eprint={2111.15629},
      archivePrefix={arXiv},
      primaryClass={cs.SI}
}
```
