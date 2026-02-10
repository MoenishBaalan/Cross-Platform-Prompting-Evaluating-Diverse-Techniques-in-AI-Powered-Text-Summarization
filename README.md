# Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

**Reg No: 212223220057**



## AIM

The objective of this study is to analyze and compare the performance of different prompting techniques—Zero-shot, Few-shot, Chain-of-Thought, and Role-based—across various AI platforms such as ChatGPT, Gemini, Claude, and Copilot for the task of text summarization.

## SCENARIO

Assume you are working as part of a content development team for an educational website that provides concise summaries of technical research papers to undergraduate students.

The task is to generate summaries for a 500-word technical article titled “The Fundamentals of Cloud Computing” using different AI platforms and prompting strategies. The effectiveness of each platform–prompt combination is evaluated based on:

Accuracy of content

Logical flow and clarity

Ease of understanding

Response time

Overall user experience

## METHODOLOGY / PROCEDURE:

### 1. Selection of Article

A technical article of approximately 500 words related to Cloud Computing was chosen for the experiment. The article included the following key concepts:

Definition and importance of cloud computing

Cloud service models (IaaS, PaaS, SaaS)

Deployment models

Real-world applications

Challenges and limitations

Input Text Summary (≈500 words)

The article explains cloud computing as a technology that enables users to access computing resources such as servers, storage, databases, and software over the internet instead of relying on local systems. This model allows organizations to reduce infrastructure costs and scale resources based on demand.

Cloud computing is commonly categorized into three service models: Infrastructure as a Service (IaaS), which provides virtualized hardware resources; Platform as a Service (PaaS), which offers development platforms and tools; and Software as a Service (SaaS), which delivers software applications through web browsers. These services eliminate the need for users to manage physical infrastructure.

The article also discusses deployment models including public cloud, private cloud, hybrid cloud, and community cloud, each offering different levels of control, security, and flexibility. Cloud computing is widely used in industries such as education, healthcare, finance, and e-commerce due to its scalability and accessibility.

However, cloud computing faces challenges such as data security concerns, dependency on internet connectivity, and compliance with regulatory requirements. Despite these limitations, cloud computing continues to play a critical role in modern digital transformation.

### 2. Prompting Techniques Used

The following prompting strategies were applied to generate summaries:

#### Zero-shot Prompt

“Summarize the given text in simple language suitable for undergraduate students.”

#### Few-shot Prompt

Two example summaries related to Artificial Intelligence and Cybersecurity were provided before requesting the cloud computing summary.

#### Chain-of-Thought Prompt

“Identify the definition of cloud computing, explain service and deployment models, describe applications and challenges, and then generate a structured summary.”

#### Role-based Prompt

“You are a Computer Science lecturer explaining cloud computing concepts to first-year students using simple examples.”

### 3. Platform-wise Execution
| Platform and Prompting Method | Observation                                                                   |
| ----------------------------- | ----------------------------------------------------------------------------- |
| ChatGPT – Zero-shot           | Produced a fast and clear summary but lacked deeper service model explanation |
| Gemini – Few-shot             | Followed example structure and generated well-organized output                |
| Claude – Chain-of-Thought     | Delivered a logically ordered and technically accurate summary                |
| Copilot – Role-based          | Very engaging explanation but slightly oversimplified technical terms         |


## EVALUATION CRITERIA

Rating Scale: 1 (Very Poor) to 5 (Excellent)

| Platform | Prompt Type      | Accuracy | Coherence | Simplicity | Speed | User Experience | Average Score |
| -------- | ---------------- | -------- | --------- | ---------- | ----- | --------------- | ------------- |
| ChatGPT  | Zero-shot        | 4        | 5         | 5          | 5     | 5               | 4.8           |
| Gemini   | Few-shot         | 5        | 4         | 4          | 4     | 4               | 4.2           |
| Claude   | Chain-of-Thought | 5        | 5         | 4          | 3     | 4               | 4.2           |
| Copilot  | Role-based       | 3        | 5         | 5          | 4     | 5               | 4.4           |


## ANALYSIS AND OBSERVATIONS

Best Accuracy: Claude (Chain-of-Thought) and Gemini (Few-shot)

Fastest Output: ChatGPT using Zero-shot prompting

Most Interactive Explanation: Copilot with Role-based prompting

Most Balanced Educational Summary: Claude with Chain-of-Thought prompting

## CONCLUSION

The experiment clearly demonstrates that the quality of AI-generated summaries strongly depends on the prompting strategy used.

Chain-of-Thought prompting with Claude produced the most structured and informative summaries

ChatGPT with Zero-shot prompting delivered the fastest response but lacked deeper technical detail

Gemini’s Few-shot prompting generated organized output but required additional setup

Copilot’s Role-based prompting enhanced engagement while reducing technical depth

Overall, Claude combined with Chain-of-Thought prompting proved to be the most effective approach for educational text summarization.

## RESULT

The cross-platform evaluation of AI summarization techniques was successfully completed.
Different prompting strategies were tested across multiple AI tools, and their outputs were assessed using defined evaluation metrics.
The results confirm that well-structured and guided prompts significantly enhance the quality of AI-generated summaries.
