
- ### SDKs & Infrastructure-as-Code
  - [SageMaker Python SDK](https://sagemaker.readthedocs.io/en/stable/)
  - [Boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker.html) and [AWS CLI](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/sagemaker/index.html)
  - [CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/AWS_SageMaker.html)
  - [CDK](https://docs.aws.amazon.com/cdk/api/v2/python/aws_cdk.aws_sagemaker.html)
  - [Terraform](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/sagemaker_domain)


- ### Containers & Frameworks
  - [Supported pre-built containers/frameworks (script mode)](https://sagemaker.readthedocs.io/en/stable/frameworks/index.html)
  - [Code] [Deep Learning Containers](https://github.com/aws/deep-learning-containers/blob/master/available_images.md)
  - [code] [Spark Containers](https://github.com/aws/sagemaker-spark-container/blob/master/available_images.md)
  - [Video] [Using Script Mode with Amazon SageMaker](https://www.youtube.com/watch?v=x94hpOmKtXM)
  - [code] [Using custom training containers](https://github.com/aws/amazon-sagemaker-examples/tree/main/advanced_functionality/custom-training-containers)
  - [code] [Training toolkit](https://github.com/aws/sagemaker-training-toolkit) and [Inference toolkit](https://github.com/aws/sagemaker-inference-toolkit)
  - [How Amazon SageMaker Provides Training Information](https://docs.aws.amazon.com/sagemaker/latest/dg/your-algorithms-training-algo-running-container.html)
  - [External] [Create reusable containers for R](https://towardsdatascience.com/how-to-create-reusable-r-containers-for-sagemaker-jobs-a3d481daf5cd)
  
- ### Data Processing
  - [SageMaker Processing](https://sagemaker.readthedocs.io/en/stable/amazon_sagemaker_processing.html#amazon-sagemaker-processing)
  - #### Large Scale Data Processing
    - [blog] [Prepare data at scale in Amazon SageMaker Studio using serverless AWS Glue interactive sessions](https://aws.amazon.com/blogs/machine-learning/prepare-data-at-scale-in-amazon-sagemaker-studio-using-serverless-aws-glue-interactive-sessions/)
    - [Video] [Using Apache Spark on Amazon EMR with SageMaker](https://www.youtube.com/watch?v=RxRENYQBxZU)
    - [Video] [Scalable data preparation using Amazon SageMaker Studio notebooks - AWS Virtual Workshop](https://www.youtube.com/watch?v=UcRNNHuYsxE)
    - [workshop] [SageMaker Studio integration with EMR Workshop](https://catalog.workshops.aws/sagemaker-studio-emr/en-US)
    - [Spark in Processing Jobs](https://sagemaker.readthedocs.io/en/stable/amazon_sagemaker_processing.html#data-processing-with-spark)
    - [Using Dask with SageMaker Processing](https://sagemaker-examples.readthedocs.io/en/latest/sagemaker_processing/feature_transformation_with_sagemaker_processing_dask/feature_transformation_with_sagemaker_processing_dask.html)
    - [Blog] [Build accurate ML training datasets using point-in-time queries with Amazon SageMaker Feature Store and Apache Spark](https://aws.amazon.com/blogs/machine-learning/build-accurate-ml-training-datasets-using-point-in-time-queries-with-amazon-sagemaker-feature-store-and-apache-spark/)
- ### Data Labeling
  - [video] [Introducing Amazon SageMaker Ground Truth Plus](https://www.youtube.com/watch?v=Y3Lo63yiqsU)
  - [external] [Labeling data with Label Studio on SageMaker](https://medium.com/geekculture/labeling-data-with-label-studio-on-sagemaker-e4b2d1b562f7)
- ### Training
  - [code] [Training - end-to-end example with Scikit-Learn](https://github.com/aws/amazon-sagemaker-examples/blob/main/sagemaker-python-sdk/scikit_learn_randomforest/Sklearn_on_SageMaker_end2end.ipynb)
  - [video] [Training - end-to-end example with Script Mode](https://www.youtube.com/watch?v=x94hpOmKtXM)
  - [code] [Using local mode](https://github.com/aws-samples/amazon-sagemaker-local-mode)
  - [code] [SageMaker Environment Variables](https://github.com/aws/sagemaker-training-toolkit/blob/master/ENVIRONMENT_VARIABLES.md)
  -  #### Distributed Training 
       - [Blog] [Choose the best data source for your Amazon SageMaker training job](https://aws.amazon.com/blogs/machine-learning/choose-the-best-data-source-for-your-amazon-sagemaker-training-job/)
       - [Blog] [Scalable Medical Computer Vision Model Training - Part 1](https://aws.amazon.com/blogs/industries/scalable-medical-computer-vision-model-training-with-amazon-sagemaker-part-1/) and [Part 2](https://aws.amazon.com/blogs/industries/scalable-medical-computer-vision-model-training-with-amazon-sagemaker-part-2)
