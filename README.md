__The content are mostly based on official SageMaker examples. Inside of the notebooks, a detailed source location is referred.__
# The following notebooks are tested on SageMaker Studio with Python3 (Tensorflow2 GPU Optimized)

### Folder : tf-sentiment-script-mode

- 1.0.scratch_sentiment.ipynb
    - Create a training script on local notebook
    - __Technique inclduded__:
        - Test a train scrpt in local notebook
- 2.0.gs-sentiment-analysis-endpoint.ipynb
    - Based on the training script, use the hosted training job using four GPUs on single instance
    - __Technique inclduded__:
        - Run a training job using 4 GPUs on a single instance with script mode
    
### Folder : tf-2-workflow

- gs-tf-2-workflow.ipynb
    - Add to create a preprocess script to be tested on local and rest of them are the same as original nversion
    - __Technique inclduded__:
        - Run a preprocessing job using 2 instances with script mode

# The following subjects are contents on notebook instances

### Folder : sagemaker-processing
- 1.0.multiple_processing.ipynb
    * __Techniques included:__
        * Test a preprocessing script on notebook
        * Prepreocess the preprocessing script on two instances
- 2.0.gs-scikit_learn_data_processing_and_model_evaluation.ipynb     
    - __Modified Points__:
        - Make new preprocess script for a local test and use it on the following code: Processing, training, evaluation, processing on the custome container


