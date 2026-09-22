# DeepSeek Jailbreak Case Study

A small research case study exploring how a structured jailbreak prompt can influence the behavior of a large language model.

## Overview

This project documents a jailbreak prompt tested against DeepSeek.

The purpose is not to claim universal model bypass capabilities, but to document and analyze a specific prompt-based behavior observed during testing.

## Repository Contents

```text
deepseek-jailbreak-case-study/
├── README.md
├── prompt.txt
├── results.md
└── LICENSE
```

### `prompt.txt`

Contains the exact prompt used during the experiment.

### `results.md`

Documents the observed behavior, analysis, and limitations of the test.

## Techniques Observed

The prompt uses several instruction-manipulation techniques, including:

* Persona manipulation
* Instruction hierarchy manipulation
* Attempts to override behavioral constraints
* User authority framing
* Forced response formatting
* Attempts to suppress refusal behavior

## Experiment Scope

This repository documents a single prompt tested against a single model.

The result should not be interpreted as proof that the technique works against other models, model versions, or deployments.

Model behavior can change as models, system instructions, and safety mechanisms are updated.

## Ethical Use

This project is intended for educational purposes, AI security research, and defensive testing.

Do not use the material in this repository to bypass safeguards for harmful, illegal, or unauthorized purposes.

## Disclaimer

This case study represents an individual experiment and does not guarantee reproducibility.

The author makes no claim that the documented prompt provides a universal or permanent method for bypassing model safeguards.

## License

This project is licensed under the MIT License.
