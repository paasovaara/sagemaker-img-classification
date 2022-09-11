# Sagemaker image classification demo

Files from [Coursera AWS Sagemaker tutorial](https://www.coursera.org/learn/aws-machine-learning/lecture/lfa8u/amazon-sagemaker-object-detection-on-images-labeled-with-ground-truth)

## Setup

- Upload the [demo.ipynb](demo.ipynb) to Sagemaker Studio and start developing
- Create an S3 bucket for input & output images, which the notebook will download
- [output.manifest](output.manifest) already contain the labeled training data, so no need to use Sagemaker Ground Truth for labelling (saving time and associated extra costs)
- It's possible that you might have to request a resource limit upgrade from AWS support for GPU instances, since by default basic accounts have a limit of 0 resources for running sagemaker training jobs. this might take a few days..
