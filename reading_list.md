<table>
    <tr>
        <td style="width:20%">
            <img src="https://learning.oreilly.com/library/cover/9781492041931/250w/" height=120/>
        </td>
        <td>
            <i><b>Building Machine Learning Powered Applications</b> by Emmanuel Ameisen</i>
            <p>
            The single most important thing I learned from this book was an architecture pattern for a simple ML pipeline. There are two parallel pipelines: inference and training. Focus is first place on building the inference pipeline that will produce simple results. Second, the training pipeline is developed to iteratively produce ML models with improved performance and additional features.
            </p>
            <h3>
            Inference Pipeline
            </h3>
            <p>
            inference data >> preprocess >> run model >> clean-up >> present
            </p>
            <h3>
            Training Pipeline
            </h3>
            <p>
            training data >> preprocess >> train >> evaluate >> save
            </p>
            <p>I'm using this architecture in two of my personal projects, using a Flask webpage for one, and a Click CLI for the other.
        </td>
    </tr>
</table>
