# Deep-Learning-Project-2-SUMMARY

Team Members: Koshiq Hossain, Thejas MS, Shreyas KV

Assessment Criteria Results:
  1. Modified BERT architecture: ✅ Used RoBERTa base model with LoRA adaptation
  2. Parameter count < 1M: ✅ Model has 814,852 trainable parameters
  3. Experimented with LoRA settings: ✅ Tested 4 different LoRA configurations
  4. Experimented with optimizer: ✅ Used rmsprop optimizer
  5. Implemented data filtering: ✅ Filtered out examples based on text length
  6. Used learning rate scheduling: ✅ Implemented linear LR schedule with warmup
  7. Comprehensive evaluation: ✅ Calculated accuracy, precision, recall, and F1 metrics
  8. Target accuracy ≥ 80%: ✅ Achieved 95.16% accuracy on eval set

Model Technical Specifications:
  Base architecture: RoBERTa
  LoRA rank parameter (r): 4
  LoRA scaling factor (alpha): 96
  Targeted network modules: ['query', 'key', 'value']
  Total parameter count: 125,463,560
  Trainable parameter count: 814,852 (0.65% of total)

Training Configuration:
  Optimization algorithm: rmsprop
  Learning rate value: 0.0001
