# Batch serving

**Batch inference** is about using data distributed processing infrastructure to carry out inference asynchronously on a large number of instances at once.

**What to optimize**: throughput, not latency-sensitive

**End user**: usually no direct interactions with a model. User interacts with the predictions stored in a data storage as a result of the batch jobs.

**Validation**: offline

---
**Examples of batch serving:**
- as a part of ETL/ELT job (Spark, MapReduce jobs)
- as a Batch pipeline in the cloud

---
## Advanced workshop: Azure Batch Serving Pipelines
This workshop is WIP

It will cover a real-life use case of building, publishing, scheduling and troubleshooting Batch Serving pipelines on Azure with Python runtime.

---
## Extras

To learn more about MLOps and batch serving:
- [Orchestrate machine learning with pipelines on Azure](https://docs.microsoft.com/en-us/learn/modules/create-pipelines-in-aml/)
- [Create Azure Machine Learning Pipeline](https://github.com/MicrosoftLearning/mslearn-dp100/blob/main/08%20-%20Create%20a%20Pipeline.ipynb)
- [Deploy batch inference pipelines with Azure Machine Learning](https://docs.microsoft.com/en-us/learn/modules/deploy-batch-inference-pipelines-with-azure-machine-learning/)
- [Create a Batch Inferencing Service on Azure](https://github.com/MicrosoftLearning/mslearn-dp100/blob/main/10%20-%20Create%20a%20Batch%20Inferencing%20Service.ipynb)
- [ETL job ML Model Deployment](https://github.com/schmidtbri/etl-job-ml-model-deployment)
- [MapReduce job ML Model Deployment](https://github.com/schmidtbri/map-reduce-ml-model-deployment)
