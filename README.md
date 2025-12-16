```markdown
# NS8 Synthetic Benchmarks

A benchmark suite for evaluating machine learning models on structured,
deterministic synthetic fields.

## Motivation
Most ML benchmarks rely on random noise or natural images.
These benchmarks test performance, but not whether a model can learn
**structure, symmetry, or temporal consistency**.

This suite provides synthetic datasets with known generative rules,
allowing controlled evaluation of model behavior.

## Tasks

### 1. Next-Slice Prediction
Given a field at phase k, predict the field at k+1.

- Tests temporal modeling
- Tests structured generalization

### 2. Symmetry Classification
Classify which transformation generated a given field.

- Tests invariance learning
- Tests representation quality

## Baseline Models
- CNN baseline
- Small transformer baseline

## Results

## Why Synthetic?
Synthetic data allows:
- infinite data
- exact ground truth
- controlled difficulty
- reproducible experiments

## Limitations
- Not a physical simulation
- Designed for evaluation, not realism
