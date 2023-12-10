# Text Transcription using Transformers to your Mother Tongue

## Model Performance Improvement Strategies

### (a) Model-Centric Approach

#### Hyperparameters used

* learning_rate: 5e-08
* train_batch_size: 16
* eval_batch_size: 8
* seed: 42
* gradient_accumulation_steps: 2
* total_train_batch_size: 32
* optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
* lr_scheduler_type: linear
* lr_scheduler_warmup_steps: 250
* training_steps: 15000
* mixed_precision_training: Native AMP

### (b) Data-Centric Approach

For slovak no other data source was found

## Results

| Model    | WER |
| -------- | ------- |
| default  | 79.861237    |
| tuned | 75.136677     |

