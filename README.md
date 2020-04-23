# CommonsenseQA Model details

# Run albert-xxlarge-v2 model (last four CLS layers concatenated) with the below parameters
```
Learning rate: 1e-5	
#GPUs: 2	
batch_size: 2	
gradient_accumulation_steps:4	
```
Then select the top 2 predictions and use another albert-xxlarge-v2 model on this new 2 way classification task.
 
For the second albert-xxlarge-v2 model use the same parameter as the first one.

