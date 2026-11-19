# Machine-Generated vs. Human Texts: A Hybrid Approach to Forensic Feature-Based Text Classification

This repository contains the data analysis outputs and evaluation results associated with the paper **“Machine-Generated vs. Human Texts: A Hybrid Approach to Forensic Feature-Based Text Classification”**, by Francisco Bernal Ortiz, Isabel Moyano Moreno, and Mario Crespo Miguel (University of Cádiz, Spain).

## Repository structure

The repository is organised into three main directories:

```text
ijimai-HFAI/
│
├── evaluations/
│   └── Text-by-text evaluation results and classification outputs
│
├── hypothesis_tests/
│   └── Statistical hypothesis testing results for linguistic features
│
├── metrics/
│   └── Classification performance metrics
│
└── README.md
```

### `evaluations/`

Contains the text-by-text evaluation results, including CSV files with the classification outcomes obtained throughout the experiments. These files provide a detailed view of the model's performance at the individual text level.

### `hypothesis_tests/`

Contains the results of the statistical hypothesis tests conducted to assess the discriminatory capacity of the linguistic features identified during the forensic linguistic analysis.

### `metrics/`

Contains the classification performance metrics used to evaluate the logistic regression models and assess their effectiveness in distinguishing between human-authored and machine-generated texts.

## Corpus

The experiments are based on the **ROBOT-TALK corpus**, which contains Spanish texts written by human authors and their AI-generated equivalents across multiple genres.

## Main findings

The results indicate that:

- Machine-generated Spanish texts exhibit identifiable linguistic patterns that can be distinguished from human-authored texts.
- Statistical hypothesis testing provides a principled basis for selecting relevant forensic linguistic features.
- Logistic regression offers an interpretable classification framework for authorship discrimination.
- GPT-3.5-Turbo achieves the most robust classification performance among the AI models evaluated.
- The integration of Likelihood Ratios contributes to the forensic interpretation of classification results.

## Research context

This work contributes to the intersection of **Forensic Linguistics**, **Computational Linguistics**, and **Artificial Intelligence Detection**. In particular, it investigates how linguistic evidence can be operationalised through statistical methods to support transparent and interpretable authorship analysis.

The study also addresses the importance of moving beyond purely accuracy-based approaches to AI-generated text detection by considering the evidentiary interpretation of statistical results.

## Authors

- **[Francisco Bernal Ortiz](https://github.com/Paco279)** — University of Cádiz, Spain.
- **[Isabel Moyano Moreno](https://github.com/isabel-mm)** — University of Cádiz, Spain.
- **[Mario Crespo Miguel](https://github.com/MarioCrespo)** — University of Cádiz, Spain.

## Citation

If you use this repository in your research, please cite the corresponding paper:

```text
Bernal Ortiz, F., Moyano Moreno, I., & Crespo Miguel, M.
Machine-Generated vs. Human Texts: A Hybrid Approach to
Forensic Feature-Based Text Classification.
```

*Publication details and DOI to be added when available.*
