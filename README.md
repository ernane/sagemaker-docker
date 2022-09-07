# Building your own algorithm container

With Amazon SageMaker, you can package your own algorithms that can than be trained and deployed in the SageMaker environment. This notebook will guide you through an example that shows you how to build a Docker container for SageMaker and use it for training and inference.

By packaging an algorithm in a container, you can bring almost any code to the Amazon SageMaker environment, regardless of programming language, environment, framework, or dependencies. 

_**Note:**_ SageMaker now includes a [pre-built scikit container](https://github.com/aws/amazon-sagemaker-examples/blob/main/sagemaker-python-sdk/scikit_learn_iris/scikit_learn_estimator_example_with_batch_transform.ipynb).  We recommend the pre-built container be used for almost all cases requiring a scikit algorithm.  However, this example remains relevant as an outline for bringing in other libraries to SageMaker as your own container.
