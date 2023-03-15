<div align="center">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Faws-samples%2Fawesome-sagemaker%2Fblob%2Fmain%2Fbuilding_ml_models.md&count_bg=%23198ED5&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false" alt="hits">
</div>

## Building ML Models

### SDKs & Infrastructure-as-Code
- [Docs] [SageMaker Python SDK](https://sagemaker.readthedocs.io/en/stable/)
- [Docs] [Boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker.html) and [AWS CLI](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/sagemaker/index.html)
- [Docs] [CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/AWS_SageMaker.html)
- [Docs] [CDK](https://docs.aws.amazon.com/cdk/api/v2/python/aws_cdk.aws_sagemaker.html)
- [Docs] [External] [Terraform](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/sagemaker_domain)

### Data Processing
- [Docs] [SageMaker Processing](https://sagemaker.readthedocs.io/en/stable/amazon_sagemaker_processing.html#amazon-sagemaker-processing)
- [Code] [Spark Containers](https://github.com/aws/sagemaker-spark-container/blob/master/available_images.md)

#### Large Scale Data Processing
- [Docs] [Spark in Processing Jobs](https://sagemaker.readthedocs.io/en/stable/amazon_sagemaker_processing.html#data-processing-with-spark)
- [Docs] [Using Dask with SageMaker Processing](https://sagemaker-examples.readthedocs.io/en/latest/sagemaker_processing/feature_transformation_with_sagemaker_processing_dask/feature_transformation_with_sagemaker_processing_dask.html)
- [Blog] [Prepare data at scale in Amazon SageMaker Studio using serverless AWS Glue interactive sessions](https://aws.amazon.com/blogs/machine-learning/prepare-data-at-scale-in-amazon-sagemaker-studio-using-serverless-aws-glue-interactive-sessions/)
- [Blog] [External] [Automating Visualization Reports with SageMaker Studio Interactive Session and Notebook Jobs](https://medium.com/@brn.pistone/streamlining-data-insights-automating-visualization-reports-with-sagemaker-studio-interactive-37d5d49480a3)
- [Blog] [Build accurate ML training datasets using point-in-time queries with Amazon SageMaker Feature Store and Apache Spark](https://aws.amazon.com/blogs/machine-learning/build-accurate-ml-training-datasets-using-point-in-time-queries-with-amazon-sagemaker-feature-store-and-apache-spark/)
- [Workshop] [SageMaker Studio integration with EMR Workshop](https://catalog.workshops.aws/sagemaker-studio-emr/en-US)
- [Video] [Using Apache Spark on Amazon EMR with SageMaker](https://www.youtube.com/watch?v=RxRENYQBxZU)
- [Video] [Scalable data preparation using Amazon SageMaker Studio notebooks - AWS Virtual Workshop](https://www.youtube.com/watch?v=UcRNNHuYsxE)

### Data Labeling
- [Video] [Introducing Amazon SageMaker Ground Truth Plus](https://www.youtube.com/watch?v=Y3Lo63yiqsU)
- [Blog] [External] [Labeling data with Label Studio on SageMaker](https://medium.com/geekculture/labeling-data-with-label-studio-on-sagemaker-e4b2d1b562f7)

### Training
- [Docs] [Supported pre-built containers/frameworks (script mode)](https://sagemaker.readthedocs.io/en/stable/frameworks/index.html)
- [Docs] [SageMaker Environment Variables](https://github.com/aws/sagemaker-training-toolkit/blob/master/ENVIRONMENT_VARIABLES.md)
- [Docs] [How Amazon SageMaker Provides Training Information](https://docs.aws.amazon.com/sagemaker/latest/dg/your-algorithms-training-algo-running-container.html)
- [Docs] [Deep Learning Containers](https://github.com/aws/deep-learning-containers/blob/master/available_images.md)
- [Blog] [Operationalize your Amazon SageMaker Studio notebooks as scheduled notebook jobs](https://aws.amazon.com/blogs/machine-learning/operationalize-your-amazon-sagemaker-studio-notebooks-as-scheduled-notebook-jobs/)
- [Blog] [Why Bring Your Own Container to Amazon SageMaker and How to do it right !](https://medium.com/@pandey.vikesh/why-bring-your-own-container-to-amazon-sagemaker-and-how-to-do-it-right-bc158fe41ed1)
- [Blog] [The Multiverse of Amazon SageMaker Toolkits](https://medium.com/@pandey.vikesh/the-multiverse-of-amazon-sagemaker-toolkits-7560c2b0f0b6)
- [Code] [Scheduled jobs on SageMaker Studio Notebooks](https://github.com/aws/amazon-sagemaker-examples/blob/main/sagemaker-notebook-jobs/studio-scheduling/scheduled-example.ipynb)
- [Code] [Training - end-to-end example with Scikit-Learn](https://github.com/aws/amazon-sagemaker-examples/blob/main/sagemaker-python-sdk/scikit_learn_randomforest/Sklearn_on_SageMaker_end2end.ipynb)
- [Code] [Using local mode](https://github.com/aws-samples/amazon-sagemaker-local-mode)
- [Code] [Using custom training containers](https://github.com/aws/amazon-sagemaker-examples/tree/main/advanced_functionality/custom-training-containers)
- [Code] [Training toolkit](https://github.com/aws/sagemaker-training-toolkit) and [Inference toolkit](https://github.com/aws/sagemaker-inference-toolkit)
- [Video] [Using Script Mode with Amazon SageMaker](https://www.youtube.com/watch?v=x94hpOmKtXM)
- [Video] [Training - end-to-end example with Script Mode](https://www.youtube.com/watch?v=x94hpOmKtXM)

#### Distributed Training 
- [Blog] [Choose the best data source for your Amazon SageMaker training job](https://aws.amazon.com/blogs/machine-learning/choose-the-best-data-source-for-your-amazon-sagemaker-training-job/)
- [Blog] [Scalable Medical Computer Vision Model Training - Part 1](https://aws.amazon.com/blogs/industries/scalable-medical-computer-vision-model-training-with-amazon-sagemaker-part-1/)
- [Blog] [Scalable Medical Computer Vision Model Training - Part 2](https://aws.amazon.com/blogs/industries/scalable-medical-computer-vision-model-training-with-amazon-sagemaker-part-2)
- [Code] [Use SageMaker with Trainium and Inferentia](https://github.com/aws-samples/sagemaker-trainium-inferentia)

