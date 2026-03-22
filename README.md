# OFT Fine-tuning for AG News Classification

## Model
- Qwen2-1.5B
- Parameter-efficient fine-tuning using OFT

## Dataset
- AG News (subset used for mini-project)
- Training samples: 2000
- Validation samples: 300
- Test samples: 300

## Task
- News topic classification (4 classes: world, sports, business, science)
- Reformulated as text generation with prompt + single word output

## Results
- Before fine-tuning: 78.52%
- After OFT fine-tuning: 90.67%
- Training loss curve included in `oft_qwen_loss_curve.png`
- Qualitative examples in notebook
