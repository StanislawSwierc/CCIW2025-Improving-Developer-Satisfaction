# Improving Developer Satisfaction through focusing on problems that provably matter


This repository contains slides presented at the 2025 CI/CD Industry Workshop (CCIW).

If you use this method in your research, please consider citing it as:
```
@inproceedings{swierc2025improving,
  author    = {Swierc, Stanislaw and Machalica, Mateusz and Yost, Scott},
  title     = {Improving Developer Satisfaction through focusing on problems that provably matter},
  year      = {2025},
  maintitle = {IEEE Conference on Software Testing, Verification and Validation (ICST)},
  booktitle = {CI/CD Industry Workshop (CCIW)},
}
```

## Abstract
In the dynamic environment of Meta, where thousands of developers manage repositories with millions of files, the DevInfra organization plays a crucial role in enhancing developer efficiency. This presentation outlines the development and implementation of top-level metrics that guide the prioritization of initiatives within DevInfra, ensuring efforts are focused on areas that significantly impact developer satisfaction. By leveraging the STEDII framework, which emphasizes Sensitivity, Trustworthiness, Efficiency, Debuggability, Interpretability, Actionability, Inclusivity, and Fairness, we established a set of reliable metrics validated through longitudinal studies and regular Developer Experience Surveys. Our approach addresses the limitations of high-level survey data by providing actionable insights through metrics. We introduced a common framework for debugging metrics, employing full, partial, and uniform blame models to attribute responsibility for negative experiences. Furthermore, the integration of these metrics with A/B testing systems allows for the assessment of potential changes before deployment, ensuring that modifications lead to genuine enhancements in developer experience. This presentation details the journey of developing these metrics, offering a replicable model for other organizations aiming to improve developer satisfaction through data-driven decision-making.

## Setup
This project uses [Pipenv](https://pipenv.pypa.io/). To create a new virtual environment and install all dependencies, use the following command:

```bash
pipenv sync
```

