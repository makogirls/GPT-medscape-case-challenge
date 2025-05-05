
# Comparative Analysis of Multimodal Large Language Models GPT-4o and o1 Versus Clinicians in clinical case challenge questions: Retrospective Cross-Sectional Study

This repository contains the code and sample datasets used in our paper titled "Comparative Analysis of Multimodal Large Language Models GPT-4 Omni and o1 Versus Clinicians in Real-World Clinical Scenarios".

---

## Abstract

**Background:** Generative Pre-trained Transformer 4 (GPT-4) has demonstrated strong performance in standardized medical examinations but has limitations in real-world clinical settings. The newly released multimodal GPT-4o model, which integrates text and image inputs to enhance diagnostic capabilities, and the multimodal o1 model, which incorporates advanced reasoning, may address these limitations.

**Objective:** This study aimed to compare the performance of GPT-4o and o1 against clinicians in real-world clinical case challenges.

**Methods:** This retrospective, cross-sectional study used Medscape case challenge questions from May 2011 to June 2024 (n = 1,426). Each case included text and images of patient history, physical examination findings, diagnostic test results, and imaging studies. Clinicians were required to choose one answer from among multiple options, with the most frequent response defined as the clinician’s decision. Data-based decisions were made using GPT models (3.5 Turbo, 4 Turbo, 4 Omni, and o1) to interpret the text and images, followed by a process to provide a formatted answer. We compared the performances of the clinicians and GPT models using Mixed-effects logistic regression analysis.

**Figure 1. Study flowchart**
<img src="https://github.com/user-attachments/assets/818951d0-c205-4e0b-8f37-c69eab463af0" alt="Sample Image" width="600" />


**Results:** Of the 1,426 questions, clinicians achieved an overall accuracy of 85.0%, whereas GPT-4o and o1 demonstrated higher accuracies of 88.4% and 94.3% (mean difference 3.4%; P = .005 and mean difference 9.3%; P < .001), respectively. In the multimodal performance analysis, which included cases involving images (n = 917), GPT-4o achieved an accuracy of 88.3%, and o1 achieved 93.9%, both significantly outperforming clinicians (mean difference 4.2%; P = .005 and mean difference 9.8%; P < .001). o1 showed the highest accuracy across all question categories, achieving 92.6% in diagnosis (mean difference 14.5%; P < .001), 97.0% in disease characteristics (mean difference 7.2%; P < .001), 92.6% in examination (mean difference 7.3%; P = .002), and 94.8% in treatment (mean difference 4.3%; P = .005), consistently outperforming clinicians. In terms of medical specialty, o1 achieved 93.6% accuracy in internal medicine (mean difference 10.3%; P < .001), 96.6% in major surgery (mean difference 9.2%; P = .030), 97.3% in psychiatry (mean difference 10.6%; P = .030), and 95.4% in minor specialties (mean difference 10.0%; P < .001), significantly surpassing clinicians. Across five trials, GPT-4o and o1 provided the correct answer 5/5 times in 86.2% and 90.7% of the cases, respectively.

<img src="https://github.com/user-attachments/assets/d7bb6707-694b-410e-ba02-1ecae01eaf4f" alt="Sample Image" width="750" />
<img src="https://github.com/user-attachments/assets/1885f46e-92bd-4289-b501-daf9cc4d2b0e" alt="Sample Image" width="750" />
<img src="https://github.com/user-attachments/assets/ad0e1e0d-a47a-4889-8ba1-b07d2c8e40e4" alt="Sample Image" width="750" />

**Conclusions:** The GPT-4o and o1 outperformed clinicians in addressing clinical challenges, particularly in disease diagnosis. The GPT-4o and o1 could serve as valuable tools to assist healthcare professionals in clinical settings.

**Keywords:** multimodal large language model; GPT-4 Omni; o1; clinical decision-making; diagnostic accuracy; artificial intelligence

**Refernece:** [https://reference.medscape.com/features/casechallenges](https://reference.medscape.com/features/casechallenges)

---

## Medscape clinical case challenge quiz sample

- **question+options.csv**: CSV file containing questions and answer options.
- **text.txt**: Text file describing the background, examination, and workup details of a patient.
- **image.jpg**: Image finding of the patient.

---

## Code Notebooks

- **GPT-3.5-Turbo.ipynb**: Notebook for evaluating GPT-3.5 Turbo's performance on clinical case challenges (Text-only inputs).
- **GPT-4-Turbo.ipynb**: Notebook for evaluating GPT-4 Turbo's performance on clinical case challenges (Text-only inputs).
- **GPT-4-Omni.ipynb**: Notebook for evaluating multimodal GPT-4 Omni's performance on clinical case challenges (Both text and image inputs).
- **o1.ipynb**: Notebook for evaluating o1's performance on clinical case challenges (Both text and image inputs).

---

## License
Comparative Analysis of Multimodal Large Language Models GPT-4o and o1 Versus Clinicians in clinical case challenge questions: Retrospective Cross-Sectional Study

Jaewon Jung, Hyunjae Kim, SungA Bae, Jin Young Park
