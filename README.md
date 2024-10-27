
# A Comparative Evaluation of GPT-4 Omni and o1-preview with Human Experts in Solving Real-World Clinical Case Challenges

## Abstract

**Background:** Although GPT-4 has demonstrated strong performance on standardized medical exams, its accuracy and reliability in real-world clinical scenarios remain limited. The newly released multimodal GPT-4 Omni model that integrates text and image inputs, along with the o1-preview model demonstrating advanced reasoning and safety features, may address these limitations. Therefore, this study aimed to compare the performance of GPT-4 Omni and o1-preview with that of human experts in solving clinical case challenges. 

**Methods:** This study included Medscape case challenge questions from May 2011 to June 2024 (n=1,426). Each case included text and images regarding background, physical examination, and workup. The challenges required human experts to choose one answer from multiple options, with the most frequent response defined as the human decision. GPT models (3.5 Turbo, 4 Turbo, 4 Omni, and o1-preview) were used to make data-based decisions by interpreting the text and images, followed by a process to provide a formatted answer. Performances of human experts and GPT models were compared using McNemar's test. 

[<img src="https://github.com/user-attachments/assets/066591b6-70f0-4097-b30a-b22b1aa3c0b0" alt="Figure 1. Study Flow" width="1000">](https://github.com/user-attachments/assets/066591b6-70f0-4097-b30a-b22b1aa3c0b0)

**Findings:** Out of 1,426 questions, both GPT-4 Omni and o1-preview outperformed human experts (88.4% vs. 85.0%, p=0.001; 93.7% vs. 85.0%, p<0.001). For 917 questions with images, GPT-4 Omni's accuracy significantly increased when images were added (88.3% vs. 86.7%, p=0.019). GPT-4 Omni specifically showed a significant advantage in disease diagnosis compared to human experts (84.9% vs. 78.1%, p<0.001). The o1-preview model surpassed human experts across all categories (diagnosis, 91.7% vs. 78.1%, p<0.001; disease characteristics, 96.0% vs. 89.8%, p<0.001, examination, 93.7% vs. 85.3%, p=0.005; treatment, 94.1% vs. 90.5%, p=0.028).

[<img src="https://github.com/user-attachments/assets/976e80e3-b4cd-4f0a-afa5-d7f57a66087f" alt="Figure 1. Study Flow" width="1000">](https://github.com/user-attachments/assets/976e80e3-b4cd-4f0a-afa5-d7f57a66087f)
[<img src="https://github.com/user-attachments/assets/8c2a00e8-c683-4051-8937-40c5c90a0490" alt="Figure 1. Study Flow" width="1000">](https://github.com/user-attachments/assets/8c2a00e8-c683-4051-8937-40c5c90a0490)

**Interpretations:** GPT-4 Omni model and o1-preview model outperformed human experts in clinical case challenges, particularly excelling in disease diagnosis. These findings suggest that GPT-4 Omni and o1-preview could serve as valuable tools to assist healthcare professionals in clinical settings, supporting various aspects of patient care and decision-making. 

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
