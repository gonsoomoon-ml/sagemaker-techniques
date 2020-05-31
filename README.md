# The following noteboos are tested on SageMaker Studio with Python3 (Tensorflow2 GPU Optimized)

### Folder : tf-sentiment-script-mode

- 1.0.scratch_sentiment.ipynb
    - Create a training script on local notebook
    - Technique inclduded:
        - Test a train scrpt in local notebook
- 2.0.gs-sentiment-analysis-endpoint.ipynb
    - Based on the training script, use the hosted training job using four GPUs on single instance
    - Technique inclduded:
        - Run a training job using 4 GPUs on a single instance with script mode
    
### Folder : tf-2-workflow

- gs-tf-2-workflow.ipynb
    - Add to create a preprocess script to be tested on local and rest of them are the same as original nversion
    - Technique inclduded:
        - Run a preprocessing job using 2 instances with script mode

    

    