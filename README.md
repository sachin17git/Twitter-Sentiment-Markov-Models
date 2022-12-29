# Twitter-Sentiment-Markov-Models
Using Markov models to detect sentiment for Covid-19 tweets.
###
First-order seems to be working well for this data.
###
`First-order` markov model
#### Performance metrics

| Metrics | `Training` | `Validation` |
| --- | --- | --- |
| `F1-score` | 0.946 | 0.635 |
| `Precision` | 0.966 | 0.809 |
| `Recall` | 0.927 | 0.522 |
| `Auc score` | 0.950 | 0.708 |

####

`Second-order` markov model
#### Performance metrics

| Metrics | `Training` | `Validation` |
| --- | --- | --- |
| `F1-score` | 0.952 | 0.563 |
| `Precision` | 0.951 | 0.601 |
| `Recall` | 0.952 | 0.530 |
| `Auc score` | 0.955 | 0.615 |
