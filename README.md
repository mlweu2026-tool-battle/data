## Dataset Description

The competition dataset is derived from the publicly available LIAR2 dataset:

- [https://huggingface.co/datasets/chengxuphd/liar2](https://huggingface.co/datasets/chengxuphd/liar2)
- [https://github.com/chengxuphd/LIAR2](https://github.com/chengxuphd/LIAR2)

We have adapted the original dataset for binary classification, reduced the number of features, and limited the dataset size to make it suitable for a time-constrained competition.

**Dataset sizes:**

- **Training dataset:** 10,000 entries
- **Test dataset:** 1,000 entries

The target column is `label`, where `1` represents fake news and `0` represents non-fake news.
