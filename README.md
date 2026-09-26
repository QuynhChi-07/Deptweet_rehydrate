# Model or Label? Confidence-Stratified Evaluation of the Mild–Moderate Boundary in Depression Severity Detection
This repository provides the code and released identifiers used in "Model or Label? Confidence-Stratified Evaluation of the Mild–Moderate Boundary in Depression Severity Detection."

## Data contains 3 columns:
Tweet ID, Label (non-depressed, mild, moderate, severe), and Confidence Score. Tweet text is not included, consistent with the source platform's developer terms. To reproduce our sample, researchers may re-hydrate the released tweet IDs using an appropriate API or rehydration tool. The recovered sample may differ slightly from ours due to content deletion or account unavailability, as documented in the sample validation analysis.

**Below are the statistics of the four depression severity levels of the released data (used in this paper, after re-hydration):**
| Depression Severity | Count |
| -------------------- | ----- |
| Non-depressed         | 2,752 |
| Mild                  | 418   |
| Moderate              | 142   |
| Severe                | 47    |

## Citation
Please also cite the original datasets this work builds on:

```bibtex
@article{kabir2022deptweet,
title = {{DEPTWEET: A typology for social media texts to detect depression severities}},
journal = {{Computers in Human Behavior}},
pages = {107503},
year = {2022},
issn = {0747-5632},
doi = {10.1016/j.chb.2022.107503},
url = {https://www.sciencedirect.com/science/article/pii/S0747563222003235},
author = {Mohsinul Kabir and Tasnim Ahmed and Md. Bakhtiar Hasan and Md Tahmid Rahman Laskar and Tarun Kumar Joarder and Hasan Mahmud and Kamrul Hasan},
keywords = {Social media, Mental health, Depression severity, Dataset},
abstract = {Mental health research through data-driven methods has been hindered by a lack of standard typology and scarcity of adequate data. In this study, we leverage the clinical articulation of depression to build a typology for social media texts for detecting the severity of depression. It emulates the standard clinical assessment procedure Diagnostic and Statistical Manual of Mental Disorders (DSM-5) and Patient Health Questionnaire (PHQ-9) to encompass subtle indications of depressive disorders from tweets. Along with the typology, we present a new dataset of 40191 tweets labeled by expert annotators. Each tweet is labeled as ‘non-depressed’ or ‘depressed’. Moreover, three severity levels are considered for ‘depressed’ tweets: (1) mild, (2) moderate, and (3) severe. An associated confidence score is provided with each label to validate the quality of annotation. We examine the quality of the dataset via representing summary statistics while setting strong baseline results using attention-based models like BERT and DistilBERT. Finally, we extensively address the limitations of the study to provide directions for further research.}
}

@inproceedings{naseem2022early,
  title={Early Identification of Depression Severity Levels on Reddit Using Ordinal Classification},
  author={Naseem, Usman and Dunn, Adam G and Kim, Jinman and Khushi, Matloob},
  booktitle={Proceedings of the ACM Web Conference 2022},
  pages={2563--2572},
  year={2022}
}

@inproceedings{turcan2019dreaddit,
  title={Dreaddit: A reddit dataset for stress analysis in social media},
  author={Turcan, Elsbeth and McKeown, Kathleen},
  booktitle={Proceedings of the tenth international workshop on health text mining and information analysis (LOUHI 2019)},
  pages={97--107},
  year={2019}
}
```
