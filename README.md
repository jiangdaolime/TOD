# Revisiting the Trade-off between the Performance of Adversarial and Normal Examples on NLP Few-shot Tasks

This repository contains a modified version of the TextAttack library, designed to enhance adversarial text attack generation and fine-tuning processes. The primary changes are made to the trainer.py file, which should be placed in the Textattack/textattack location of the TextAttack version 0.3.7 for proper functionality.

# Installation
Clone the repository:
```bash
git clone https://github.com/jiangdaolime/TOD.git
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Install TextAttack:
Follow the installation instructions for TextAttack from their official repository.

Replace the modified file:
Copy the trainer.py file from this repository and replace the corresponding file in your local TextAttack installation at TextAttack/textattack

# Usage
To generate adversarial samples and use them for fine-tuning, follow the standard TextAttack procedures. Detailed usage can be found in the TextAttack documentation.

## Adversarial Sample Generation
You can generate adversarial samples using various attack methods provided by TextAttack. Once generated, these samples can be fine-tuned as per your requirements. The creation process can be referenced from the TextAttack official documentation.

## Reusing Adversarial Samples
To reuse adversarial samples, store them in a CSV file and load them as needed. We have provided a sample data file in the repository for reference. For additional data or queries, please contact the authors or generate new adversarial samples using the attack methods provided.

## Fine-Tuning Process
The entire fine-tuning workflow can be referenced from the pseudocode section of our paper.


# Contributing
We welcome contributions to improve this repository. Please fork the project, create a feature branch, and submit a pull request.


# Contact
For more information, questions, or additional data, please contact the authors at [ningrx21@gmail.com].

