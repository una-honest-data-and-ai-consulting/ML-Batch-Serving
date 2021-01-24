# Hands-on with ML serving pipelines

## Batch serving

**Batch inference** is about using data distributed processing infrastructure to carry out inference asynchronously on a large number of instances at once.

**What to optimize**: throughput, not latency-sensitive

**End user**: usually no direct interactions with a model. User interacts with the predictions stored in a data storage as a result of the batch jobs.

**Validation**: offline
