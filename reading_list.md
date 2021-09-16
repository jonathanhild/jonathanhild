# Reading List

<img src="https://learning.oreilly.com/library/cover/9781492045106/250w/" style="width:120px;"/>

## _**Building Machine Learning Powered Applications** by Emmanuel Ameisen_

The single most important thing from this book was an architecture pattern for a simple ML pipeline. There are two parallel pipelines: inference and training. Focus is first place on building the inference pipeline that will produce simple results. Second, the training pipeline is developed to iteratively produce ML models with improved performance and additional features.

*Inference Pipeline*

    inference data >> preprocess >> run model >> clean-up >> present

*Training Pipeline*

    training data >> preprocess >> train >> evaluate >> save

"Save" in the training pipeline then connects to the "run model" step in the inference pipeline. I'm using this architecture in two of my personal projects, using a Flask webpage for one, and a Click CLI for the other.

---
