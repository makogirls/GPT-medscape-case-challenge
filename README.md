
# Comparative Analysis of Multimodal Large Language Models GPT-4o and o1 Versus Clinicians in Clinical Case Challenge Questions

This repository contains the code and sample datasets used in our paper titled "Comparative Analysis of Multimodal Large Language Models GPT-4o and o1 Versus Clinicians in Clinical Case Challenge Questions".

---

## Abstract

**Background:** Generative Pre-trained Transformer 4 (GPT-4) has demonstrated strong performance in standardized medical examinations but has limitations in real-world clinical settings. To address these limitations, the multimodal GPT-4o model integrates text and image inputs, and the multimodal o1 model incorporates advanced reasoning.

**Objective:** This study compared the performance of GPT-4o and o1 against that of Medscape respondents (majority vote) in real-world clinical case challenges.

**Methods:** This retrospective, cross-sectional study used 1,426 Medscape case challenge questions from May 2011 to June 2024. Each case included text and images of patient history, physical examinations, diagnostic tests, and imaging studies. Medscape respondents were required to choose one answer from among multiple options, with the most frequent response defined as the Medscape respondent’s decision. GPT models (3.5 Turbo, 4 Turbo, 4 Omni, and o1) were used to interpret the text and images and generate formatted responses. We compared the performances of the Medscape respondents and GPT models using mixed-effects logistic regression analysis.

**Figure 1. Study flowchart**

<img src="https://github.com/user-attachments/assets/15c01d04-ace9-4caa-9ba4-9a511d7d3dfd" alt="Sample Image" width="750" />

**Results:** Medscape respondents (majority vote) achieved an overall accuracy of 85.0%, whereas GPT-4o and o1 demonstrated higher accuracies of 88.4% (P = .005) and 94.3% (P < .001), respectively. In multimodal analysis involving images (n = 917), GPT-4o achieved an accuracy of 88.3% (P = .005), while o1 achieved 93.9% (P < .001), both significantly outperforming Medscape respondents. o1 demonstrated the highest accuracy across all question categories, achieving 92.6% (P < .001) in diagnosis, 97.0% (P < .001) in disease characteristics, 92.6% (P = .002) in examination, and 94.8% (P = .005) in treatment. In terms of medical specialty, o1 achieved 93.6% (P < .001) accuracy in internal medicine, 96.6% (P = .030) in major surgery, 97.3% (P = .030) in psychiatry, and 95.4% (P < .001) in minor specialties, significantly surpassing Medscape respondents. Across five trials, GPT-4o and o1 provided the correct answer 5/5 times in 86.2% and 90.7% of the cases, respectively.

**Figure 2. Overall performance of GPT models**

<img src="https://github.com/user-attachments/assets/c52522e1-2297-4e60-9b2a-5cf8dbd1b5b5" alt="Sample Image" width="750" />
<img src="https://github.com/user-attachments/assets/c3fe5be6-f345-45c4-aec4-ec61549ff938" alt="Sample Image" width="750" />
<img src="https://github.com/user-attachments/assets/57d750f7-b519-4bab-813f-b372f29e1eea" alt="Sample Image" width="750" />

**Conclusions:** The GPT-4o and o1 models achieved higher accuracy than Medscape respondents (majority vote) in clinical case evaluations, particularly in disease diagnosis. GPT-4o and o1 could serve as valuable tools to assist healthcare professionals in structured scenarios.

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
This project refers to the preprint:

Jung, J., Kim, H., Bae, S., & Park, J. Y. (2025, June 23). Comparative Analysis of Multimodal Large Language Models GPT-4o and o1 Versus Clinicians in Clinical Case Challenge Questions. medRxiv. https://doi.org/10.1101/2025.06.22.25330068

© 2025 the author/funder. This preprint is made available under the Creative Commons Attribution‑NonCommercial 4.0 International License (CC BY‑NC 4.0).
