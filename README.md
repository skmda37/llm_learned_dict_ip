# About

We define the learnable query dictioanry via trainable inputs (soft prompts) to a LLM. The dictionary can be optimized in two ways: (1) REINFORCE; (2) straight-through.

## REINFORCE
Use V-IP objective as reward. Sample various query realizations and compute their likelihood. Apply REINFORCE to differentiate expected reward.

### REINFORCE with Baseline
To stabilize REINFORCE let's use a baseline trick.

## Straight-Through
Not sure yet how this would work.
