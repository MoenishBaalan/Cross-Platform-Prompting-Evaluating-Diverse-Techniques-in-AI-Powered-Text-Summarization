# Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

**Reg No: 212223220057**

---

## AIM

The objective of this study is to analyze and compare the performance of different prompting techniques—Zero-shot, Few-shot, Chain-of-Thought, and Role-based—across various AI platforms such as ChatGPT, Gemini, Claude, and Copilot for the task of text summarization.

## SCENARIO

Assume you are working as part of a content development team for an educational website that offers concise summaries of technical research papers to undergraduate students.

The task is to generate summaries for a 500-word technical article titled “The Basics of Blockchain Technology” using different AI platforms and prompting strategies.
The effectiveness of each platform–prompt combination is evaluated based on:

Accuracy of content

Logical flow and clarity

Ease of understanding

Response time

Overall user experience


## METHODOLOGY / PROCEDURE

### 1. Selection of Article

A technical article of approximately 500 words related to Blockchain Technology was chosen for the experiment. The article included the following key concepts:

Meaning and purpose of blockchain

Block structure and cryptographic hashing

Consensus techniques

Practical applications

Limitations and challenges

Input Text Summary (≈500 words):
The article explains blockchain as a decentralized digital ledger system that records transactions across multiple computers without relying on a central authority. Introduced in 2008 by Satoshi Nakamoto for Bitcoin, blockchain addressed the issue of double spending through cryptographic security.

Each block in the blockchain stores transaction data, a timestamp, and a hash of the previous block. Any modification in a block alters its hash, breaking the chain and making tampering easily detectable. Consensus mechanisms like Proof of Work and Proof of Stake ensure agreement among network participants. While Proof of Work offers strong security, it consumes high energy.

Beyond cryptocurrencies, blockchain is used in supply chain tracking, healthcare data management, and smart contracts on platforms such as Ethereum. However, scalability issues and regulatory uncertainty continue to limit widespread adoption. Despite these challenges, blockchain is considered a transformative technology for establishing digital trust.

### 2. Prompting Techniques Used

The following prompting strategies were applied to generate summaries:

### Zero-shot Prompt

“Summarize the given text in simple language suitable for undergraduate students.”

### Few-shot Prompt

Two example summaries related to Cloud Computing and AI Ethics were provided before requesting the blockchain summary.

### Chain-of-Thought Prompt

“Identify the definition of blockchain, explain its components, describe applications and challenges, and then create a structured summary.”

### Role-based Prompt

“You are a Computer Science lecturer explaining blockchain concepts to first-year students using easy examples.”

### 3. Platform-wise Execution
Platform and Prompting Method	Observation
ChatGPT – Zero-shot	Generated a quick and clear summary but skipped some cryptographic details
Gemini – Few-shot	Followed the sample pattern well and produced organized output
Claude – Chain-of-Thought	Delivered a logically structured and technically detailed summary
Copilot – Role-based	Very engaging explanation but simplified some technical concepts


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

The experiment clearly demonstrates that the quality of AI-generated summaries depends heavily on the prompting strategy used.

Chain-of-Thought prompting with Claude produced the most structured and informative summaries.

ChatGPT with Zero-shot prompting offered the fastest response but lacked deeper technical details.

Gemini’s Few-shot prompting generated well-organized content but required additional setup.

Copilot’s Role-based prompting enhanced engagement but reduced technical accuracy.

Overall, Claude combined with Chain-of-Thought prompting proved to be the most effective approach for educational text summarization.


## RESULT

The cross-platform evaluation of AI summarization techniques was successfully completed.
Different prompting strategies were tested across multiple AI tools, and their outputs were assessed using defined evaluation metrics.
The results confirm that well-structured and guided prompts significantly enhance the quality of AI-generated summaries.
