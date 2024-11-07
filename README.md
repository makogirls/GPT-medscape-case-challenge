
# A Comparative Evaluation of GPT-4 Omni and o1-preview with Human Experts in Solving Real-World Clinical Case Challenges

This repository contains the code and sample datasets used in our paper titled "A Comparative Evaluation of GPT-4 Omni and o1-preview with Human Experts in Solving Real-World Clinical Case Challenges".

---

## Abstract

**Background:** GPT-4 has demonstrated strong performance in standardised medical examinations. However, its accuracy and reliability in real-world clinical scenarios are limited. The newly released multimodal GPT-4 Omni model, which integrates text and image inputs to enhance diagnostic capabilities, and the o1-preview model, which incorporates advanced reasoning, improved contextual understanding, and enhanced safety features, may address these limitations together. This study aimed to compare the performances of GPT-4 Omni and o1-preview with that of human experts in solving clinical case challenges.

**Methods:** We used Medscape case challenge questions from May 2011 to June 2024 (n=1,426). For each case, we included text and images regarding the background, physical examination, and workup. Human experts were required to choose one answer from multiple options, with the most frequent response defined as the human decision. Data-based decisions were made using GPT models (3·5 Turbo, 4 Turbo, 4 Omni, and o1-preview) to interpret text and images, followed by a process to provide a formatted answer. We compared the performances of human experts and GPT models using the McNemar test.

[<img src="https://github.com/user-attachments/assets/703cb0f4-4b93-432b-a90c-8b42e1cc14f0" alt="Figure 1. Study Flow" width="700">](https://github.com/user-attachments/assets/703cb0f4-4b93-432b-a90c-8b42e1cc14f0)

**Findings:** Of the 1,426 questions, human experts had 85·0% accuracy. The o1-preview model and GPT-4 Omni significantly outperformed them, achieving accuracies of 93·7% (p < 0.001) and 88·4% (p = 0·001), respectively. The o1-preview model demonstrated the highest accuracy across all question categories, consistently outperforming human experts. The accuracy of GPT-4 Omni improved from 86·7% with text input alone to 88·3% when images were included (p = 0·019). Across five trials, the o1-preview model and the GPT-4 Omni consistently provided correct answers in 89·6% and 86·2% of cases.

[<img src="https://github.com/user-attachments/assets/d73fe7f3-4b00-4849-b11e-6696c9bb4ddc" alt="Figure 1. Study Flow" width="700">](https://github.com/user-attachments/assets/d73fe7f3-4b00-4849-b11e-6696c9bb4ddc)
[<img src="https://github.com/user-attachments/assets/e9087757-a919-46ae-b949-2723f0eb9f8f" alt="Figure 1. Study Flow" width="700">](https://github.com/user-attachments/assets/e9087757-a919-46ae-b949-2723f0eb9f8f)

**Interpretations:** GPT-4 Omni and o1-preview outperformed human experts in addressing clinical case challenges, particularly in disease diagnosis. GPT-4 Omni and o1-preview could serve as valuable tools to assist healthcare professionals in clinical settings, supporting various aspects of patient care and decision-making.

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
- **o1-preview.ipynb**: Notebook for evaluating o1-preview's performance on clinical case challenges (Text-only inputs).

---

## License
A Comparative Evaluation of GPT-4 Omni and o1-preview with Human Experts in Solving Real-World Clinical Case Challenges  
Jaewon Jung, Hyunjae Kim, SungA Bae, Jin Young Park
