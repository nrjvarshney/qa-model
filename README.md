# CommonsenseQA 

# Model Details

## Run albert-xxlarge-v2 model (last four CLS layers concatenated) with the below parameters
```
Learning rate: 1e-5	
#GPUs: 2	
batch_size: 2	
gradient_accumulation_steps:4	
```
## Then select the top 2 predictions from the train set to train another albert-xxlarge-v2 model on this new 2 way classification task.

## Repeat the same process for the test set.  
### Note: For the second albert-xxlarge-v2 model use the same parameter as the first one.

