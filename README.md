
# A Comparative Evaluation of GPT-4 Omni and o1-preview with Human Experts in Solving Real-World Clinical Case Challenges

This repository contains the code and sample datasets used in our paper titled "A Comparative Evaluation of GPT-4 Omni and o1-preview with Human Experts in Solving Real-World Clinical Case Challenges", available at [https://**********](https://**********).

---

## Abstract

**Background:** Although GPT-4 has demonstrated strong performance on standardized medical exams, its accuracy and reliability in real-world clinical scenarios remain limited. The newly released multimodal GPT-4 Omni model, which integrates text and image inputs to enhance diagnostic capabilities, along with the o1-preview model, which incorporates advanced reasoning, improved contextual understanding, and enhanced safety features, may together address these limitations. Therefore, this study aimed to compare the performance of GPT-4 Omni and o1-preview with that of human experts in solving clinical case challenges.

**Methods:** This study included Medscape case challenge questions from May 2011 to June 2024 (n=1,426). Each case included text and images regarding background, physical examination, and workup. The challenges required human experts to choose one answer from multiple options, with the most frequent response defined as the human decision. GPT models (3.5 Turbo, 4 Turbo, 4 Omni, and o1-preview) were used to make data-based decisions by interpreting the text and images, followed by a process to provide a formatted answer. Performances of human experts and GPT models were compared using McNemar's test.

[<img src="https://github.com/user-attachments/assets/703cb0f4-4b93-432b-a90c-8b42e1cc14f0" alt="Figure 1. Study Flow" width="700">](https://github.com/user-attachments/assets/703cb0f4-4b93-432b-a90c-8b42e1cc14f0)

**Findings:** In a study involving 1,426 questions, human experts had an accuracy of 85.0%; the o1-preview model and GPT-4 Omni significantly outperformed them, achieving accuracies of 93.7% (p < 0.001) and 88.4% (p = 0.001), respectively. The o1-preview model demonstrated the highest accuracy across all question categories, consistently outperforming human experts. GPT-4 Omni's accuracy improved from 86.7% with text input alone to 88.3% when images were included (p = 0.019). Over five trials, the o1-preview model provided consistently correct answers in 89.6% of cases, and GPT-4 Omni was consistently correct in 86.2% of cases.

[<img src="https://github.com/user-attachments/assets/d73fe7f3-4b00-4849-b11e-6696c9bb4ddc" alt="Figure 1. Study Flow" width="700">](https://github.com/user-attachments/assets/d73fe7f3-4b00-4849-b11e-6696c9bb4ddc)
[<img src="https://github.com/user-attachments/assets/e9087757-a919-46ae-b949-2723f0eb9f8f" alt="Figure 1. Study Flow" width="700">](https://github.com/user-attachments/assets/e9087757-a919-46ae-b949-2723f0eb9f8f)

**Interpretations:** GPT-4 Omni model and o1-preview model outperformed human experts in clinical case challenges, particularly excelling in disease diagnosis. These findings suggest that GPT-4 Omni and o1-preview could serve as valuable tools to assist healthcare professionals in clinical settings, supporting various aspects of patient care and decision-making.

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
Jaewon Jung, Hyunjae Kim, SungA Bae
