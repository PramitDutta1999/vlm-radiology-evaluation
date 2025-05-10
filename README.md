# vlm-radiology-evaluation
# From Pixels to Insights: Exploring Vision Language Models in Healthcare

This repository explores the application of Vision-Language Models (VLMs) in the healthcare domain, particularly for medical image understanding. The study evaluates three models — BiomedCLIP, BLIP, and Florence — highlighting their strengths, limitations, and performance in radiology-based tasks.

## Overview

- **BiomedCLIP**: A domain-adapted version of CLIP, trained on biomedical image-text pairs.
- **BLIP**: A general-purpose vision-language model with generative capabilities.
- **Florence**: A model trained using visual question-answering (VQA) tasks with structured prompts.

The analysis focuses on evaluating zero-shot and few-shot capabilities of these models using datasets like ROCO and MedVQA.

## Key Findings

- **Domain adaptation** (as seen in BiomedCLIP) significantly improves medical image-text alignment.
- **Generalist models** like BLIP struggle with clinical context without domain-specific fine-tuning.
- **Florence** shows moderate improvement post-training but is limited by short training duration and computational constraints.

## Datasets Used

- **ROCO** (Radiology Objects in Context)
- **MedVQA** (Medical Visual Question Answering)

## Evaluation Metrics

- **Raw similarity score** (for BiomedCLIP)
- **Cosine similarity** (for BLIP)
- **Expert answer comparison** (for Florence)

## Code Availability

The source code for this project is **not publicly included** in this repository. If you want to access the code or report, please contact the author at [pramitduttaanik@gmail.com] (mailto:pramitduttaanik@gmail.com).


## 📬 Contact

For questions or collaborations, please reach out to:

- Pramit Dutta — [pramitduttaanik@gmail.com] (mailto:pramitduttaanik@gmail.com)

---

*This project was completed as part of the ENGG*6302 Image Processing course at the University of Guelph.*



