
# Comparative Analysis of Multimodal Large Language Models GPT-4 Omni and o1 Versus Clinicians in Real-World Clinical Scenarios

This repository contains the code and sample datasets used in our paper titled "Comparative Analysis of Multimodal Large Language Models GPT-4 Omni and o1 Versus Clinicians in Real-World Clinical Scenarios".

---

## Abstract

**Background:** GPT-4 has demonstrated strong performance in standardized medical exams but faces limitations in real-world clinical settings. The newly released multimodal GPT-4 Omni model, which integrates text and image inputs to enhance diagnostic capabilities, and the multimodal o1 model, which incorporates advanced reasoning, improved contextual understanding, and enhanced safety features, may address these limitations together.

**Objective:** Comparative Analysis of Multimodal Large Language Models GPT-4 Omni and o1 Versus Clinicians in Real-World Clinical Scenarios.

**Methods:** We used Medscape case challenge questions from May 2011 to June 2024 (n = 1,426). Each case included text and images regarding patient history, physical examination findings, diagnostic test results, and imaging studies. Clinicians were required to choose one answer from multiple options, with the most frequent response defined as the clinicians’ decision. Data-based decisions were made using GPT models (3.5 Turbo, 4 Turbo, 4 Omni, and o1) to interpret text and images, followed by a process to provide a formatted answer. We compared the performances of clinicians and GPT models using the McNemar test.

<img src="https://github.com/user-attachments/assets/5852b1e8-efab-4aaf-9a44-c988d677feb0" alt="Sample Image" width="500" />

**Results:** Of the 1,426 questions, clinicians achieved an overall accuracy of 85.0%, while GPT-4 Omni and o1 demonstrated higher accuracies of 88.4% and 94.3% (p = 0.001 and p < 0.001), respectively. In the multimodal performance analysis, which included cases involving images (n = 917), GPT-4 Omni achieved an accuracy of 88.3% and o1 achieved 93.9%, both significantly outperforming clinicians (p < 0.001 and p < 0.001). o1 showed the highest accuracy across all question categories, achieving 92.6% in diagnosis (p < 0.001), 97.0% in disease characteristics (p < 0.001), 92.6% in examination (p = 0.008), and 94.8% in treatment (p = 0.016), consistently outperforming clinicians. By medical specialty, o1 achieved 93.6% accuracy in internal medicine (p < 0.001), 96.6% in major surgery (p = 0.011), 97.3% in psychiatry (p = 0.011), and 95.4% in minor specialties (p < 0.001), significantly surpassing clinicians. Across five trials, GPT-4 Omni and o1 consistently provided correct answers in 86.2% and 90.7% of cases, respectively.

<img src="https://github.com/user-attachments/assets/023c5aab-27c1-430c-91bb-f5b5a6b0b80c" alt="Sample Image" width="600" />
<img src="https://github.com/user-attachments/assets/1885f46e-92bd-4289-b501-daf9cc4d2b0e" alt="Sample Image" width="600" />
<img src="https://github.com/user-attachments/assets/ad0e1e0d-a47a-4889-8ba1-b07d2c8e40e4" alt="Sample Image" width="600" />

**Conclusions:** GPT-4 Omni and o1 outperformed clinicians in addressing clinical case challenges, particularly in disease diagnosis. GPT-4 Omni and o1 could serve as valuable tools to assist healthcare professionals in clinical settings, supporting various aspects of patient care and decision-making.

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
- **o1.ipynb**: Notebook for evaluating o1-preview's performance on clinical case challenges (Text-only inputs).

---

## License
A Comparative Evaluation of GPT-4 Omni and o1-preview with Human Experts in Solving Real-World Clinical Case Challenges  
Jaewon Jung, Hyunjae Kim, SungA Bae, Jin Young Park
