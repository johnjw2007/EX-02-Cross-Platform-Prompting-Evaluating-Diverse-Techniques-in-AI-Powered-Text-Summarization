EX-02 – Cross-Platform Prompting: Evaluating Diverse Prompt Structures in AI-Powered Text Summarization

## AIM
To design, develop, and evaluate different prompt structures for AI-powered text summarization by progressively improving a basic prompt using Role, Context, Constraint, and Output Format techniques.

## OBJECTIVE

To practice prompt engineering by applying different prompt structures to a specific application, Text Summarization, and observe how the quality of the generated summary improves from a basic prompt to a well-defined final prompt.

The following prompt structures are used:

Basic Prompt
Role Prompt
Context Prompt
Constraint Prompt
Output Format Prompt
Final Combined Prompt

## SCENARIO

You are part of a content curation team for an educational platform that provides simplified summaries of technical topics to undergraduate students.

The selected application is Text Summarization, and the input article is:

The Basics of Blockchain Technology

Blockchain technology has rapidly emerged as one of the most transformative innovations of the 21st century. Initially developed as the foundation for cryptocurrencies like Bitcoin, it has since expanded into industries such as finance, supply chain management, healthcare, and voting systems. At its core, blockchain is a decentralized and transparent digital ledger that securely records transactions across multiple computers.

Blockchain consists of a chain of digital blocks containing transaction data, a timestamp, and a cryptographic hash of the previous block. The hash helps protect the integrity of the blockchain because modifying one block would require changes to subsequent blocks.

A blockchain transaction begins when a user initiates a transaction. The transaction is broadcast to network nodes for verification using consensus mechanisms such as Proof of Work or Proof of Stake. Once verified, transactions are grouped into a block. The block is linked to the existing chain using cryptographic hashes, and the updated blockchain is distributed across the network.

The major features of blockchain include decentralization, transparency, immutability, and security. Unlike traditional databases controlled by a central authority, blockchain distributes information across multiple computers. This reduces the risk of manipulation and provides greater transparency.

Blockchain has applications beyond cryptocurrency. In finance, it can support faster cross-border payments. In supply chain management, it can help track products from production to delivery. Healthcare organizations can use blockchain to securely share patient information. Blockchain-based voting systems can improve transparency, while smart contracts can automatically execute agreements when predefined conditions are met.

Overall, blockchain represents a major change in how digital information and transactions can be recorded, verified, and shared. Its decentralized, transparent, and secure nature makes it useful across many industries.

## ALGORITHM
Step 1 – Select Application

Select Text Summarization as the application for prompt engineering.

Step 2 – Select Input Text

Use the same article, "The Basics of Blockchain Technology", for every prompt.

Step 3 – Create Basic Prompt

Start with a simple instruction without additional context or constraints.

Step 4 – Add Role

Modify the prompt by assigning a specific role to the AI.

Step 5 – Add Context

Provide information about the target audience and purpose of the summary.

Step 6 – Add Constraints

Define specific requirements such as length, language level, and information that must be retained.

Step 7 – Define Output Format

Specify exactly how the generated summary should be presented.

Step 8 – Create Final Prompt

Combine all the prompt structures into one optimized prompt.

Step 9 – Compare Outputs

Compare the generated summaries based on:

Accuracy
Coherence
Simplicity
Relevance
Completeness
Step 10 – Identify Improvement

Determine how progressively adding prompt elements improves the quality and usefulness of the generated summary.

## PROMPT DESIGN
1. Basic Prompt

The basic prompt provides only the task without additional instructions.

Prompt:

Summarize the following article on "The Basics of Blockchain Technology" in a concise manner.

Purpose:
To establish a baseline for comparison.

2. Role Prompt

A specific role is assigned to the AI to influence the style and perspective of the response.

Prompt:

Act as a university professor teaching undergraduate students. Summarize the following article on "The Basics of Blockchain Technology" in a way that is easy for students to understand.

Purpose:
To make the explanation more educational and student-friendly.

3. Context Prompt

Context explains who the summary is for and why it is required.

Prompt:

You are preparing study material for undergraduate computer science students who have limited knowledge of blockchain technology. Summarize the following article so that students can quickly understand the basic concept, working process, key features, and applications of blockchain.

Purpose:
To make the generated summary relevant to the intended audience and use case.

4. Constraint Prompt

Constraints specify boundaries that the AI should follow.

Prompt:

Summarize the following article on "The Basics of Blockchain Technology" for undergraduate students. Keep the summary between 120 and 150 words. Use simple English and avoid unnecessary technical jargon. Include the definition of blockchain, how it works, its major features, and important applications. Do not introduce information that is not present in the article.

Purpose:
To control the length, language, content, and accuracy of the output.

5. Output Format Prompt

The desired structure of the response is explicitly defined.

Prompt:

Summarize the following article on "The Basics of Blockchain Technology". Present the answer using the following format:

1. What is Blockchain?
2. How Does it Work?
3. Key Features
4. Applications
5. Conclusion

Use simple language suitable for undergraduate students and keep each section concise.

Purpose:
To make the output organized, readable, and easy to study.

6. FINAL COMBINED PROMPT

The final prompt combines Role + Context + Constraint + Output Format.

Prompt:

Act as a university professor preparing study material for first-year undergraduate students who have limited prior knowledge of blockchain technology.

The purpose is to create a quick and easy-to-understand study summary of the article "The Basics of Blockchain Technology" provided below.

Summarize the article in 120–150 words using simple English. Avoid unnecessary technical jargon. Make sure the summary accurately covers the definition of blockchain, its working process, key features, and major applications. Do not introduce information that is not present in the original article.

Present the summary using the following structure:

1. What is Blockchain? – Brief definition
2. How Does it Work? – Main working steps
3. Key Features – Important characteristics
4. Applications – Major real-world uses
5. Conclusion – One or two sentences summarizing its importance

Ensure that the final answer is clear, logically organized, concise, and suitable for undergraduate students.

Article:
The Basics of Blockchain Technology
[Paste the selected article here]

## EXPECTED PROGRESSION
Prompt Structure	Main Improvement
Basic Prompt	Performs the task with minimal instruction
Role Prompt	Makes the response suitable for a particular perspective
Context Prompt	Makes the response relevant to the target audience and purpose
Constraint Prompt	Controls length, language, and required information
Output Format Prompt	Produces a structured and readable response
Final Prompt	Combines all techniques for a more precise result
EVALUATION CRITERIA

Each generated summary can be evaluated using a 1–5 scale.

## Criterion	Description
Accuracy	Correctly represents the information in the original article
Coherence	Ideas are logically organized and easy to follow
Simplicity	Language is understandable for undergraduate students
Relevance	Focuses only on important information
Completeness	Covers the major concepts from the original article
Scoring
5 – Excellent
4 – Very Good
3 – Good
2 – Fair
1 – Poor

## RESULT TABLE

You can use a table like this after actually running the prompts:

Prompt Type	Accuracy	Coherence	Simplicity	Relevance	Completeness	Total / 25
Basic Prompt	4	4	4	4	3	19
Role Prompt	5	4	5	4	4	22
Context Prompt	5	5	5	5	4	24
Constraint Prompt	5	5	5	5	5	25
Output Format Prompt	5	5	5	5	5	25
Final Combined Prompt	5	5	5	5	5	25

## RESULT

The experiment demonstrated that prompt quality improves progressively when additional prompt structures are introduced. The Basic Prompt produced a general summary but provided limited control over the response. Adding a Role Prompt improved the suitability of the explanation for undergraduate students. The Context Prompt further improved relevance by specifying the target audience and purpose.

The Constraint Prompt provided greater control over summary length, language, and required information. The Output Format Prompt improved organization and readability by defining a clear structure. The Final Combined Prompt, which incorporated role, context, constraints, and output format, produced the most controlled and consistent result.

Therefore, structured prompting is more effective than a basic prompt for generating accurate, relevant, simple, and well-organized technical summaries.

## CONCLUSION

The experiment successfully demonstrated the importance of prompt engineering in AI-powered text summarization. Starting from a basic prompt and progressively adding role, context, constraints, and output formatting resulted in better-controlled outputs. The Final Combined Prompt provided the highest level of control and is the most suitable approach for generating educational summaries for undergraduate students.
