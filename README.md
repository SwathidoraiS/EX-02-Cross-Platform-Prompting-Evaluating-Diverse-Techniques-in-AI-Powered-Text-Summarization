# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm
The experiment evaluates leading AI platforms—ChatGPT, Gemini, Perplexity, Google AI, and Meta—using the same prompt and identical conditions. Outputs are scored for accuracy, clarity, depth, relevance, and response time, and the performance data is summarized in a comparison table to identify the most effective platform for technical summarization or Q&A.

## ChatGPT
Output Style: Creative, human-like, detailed, clear, with deep reasoning and well-structured paragraphs.

#### Sample Answer:
"Blockchain technology is a decentralized system for recording transactions that ensures transparency and security without intermediaries. Each block contains data and links to previous blocks, forming a chain that is immutable and distributed across a network. This system enables secure digital transactions, is central to cryptocurrencies, and shows promise for broader applications such as supply chain management and voting systems."

#### Strengths:
High depth and clarity, excellent coherence, great for explanatory and creative summarization tasks.

## Gemini (Google DeepMind)
Output Style: Accurate, up-to-date, integrates facts from Google search, concise, formal tone.

#### Sample Answer:
"Blockchain is a distributed ledger technology used for securely recording and verifying digital transactions. It works by storing information in chained blocks, which are validated collectively by a peer-to-peer network. Key strengths include transparency, security, and resistance to tampering, supporting uses in finance, logistics, and verification of digital assets."

#### Strengths:
Recent factual data, logical organization, strong relevance for time-sensitive topics, good context integration.

## Perplexity AI
Output Style: Direct, cited, concise, fact-focused, with source references, ideal for academic or research needs.

#### Sample Answer:
"Blockchain technology is a decentralized ledger that records transactions in sequential blocks, ensuring data transparency and immutability. It supports digital currencies by removing centralised control and is also applied in industries like healthcare and logistics for secure data sharing."

#### Strengths:
Transparent answers with citations, real-time data retrieval, highly accurate for research and fact-checking, rapid responses.

## Google AI (Bard/Generic Google AI)
Output Style: Balanced, integrates search, multimodal options, structured but occasionally generic.

#### Sample Answer:
"Blockchain is an open, secure way to track digital transactions by linking records in a chain. Its main features—decentralization, consensus, and immutability—make it attractive for financial, supply chain, and authentication solutions. The technology evolves quickly, with new frameworks and uses emerging frequently."

#### Strengths:
Leverages Google search/data, handles various input types, suitable for integrated workflow queries, reliable for general summaries.

## Meta (LLAMA, etc.)
Output Style: Direct, moderately detailed, sometimes less technical depth, less context adaptation.

#### Sample Answer:
"Blockchain keeps records of digital transactions by grouping them into linked blocks. Networks verify these blocks, making it difficult to alter past records. This system is mostly used in cryptocurrencies but is expanding into other real-world applications."

#### Strengths:
Fast response, suitable for general summarization and basic technical explanations, utility across broad domains, but less specialized than others

### Comparative Results Table (Muthulakshmi D)
<img width="900" height="277" alt="image" src="https://github.com/user-attachments/assets/c0b484a2-9042-493b-9d01-d60cacb9398d" />


ChatGPT excels in technical summarization, delivering the most consistent results for accuracy, clarity, depth, and relevance.

Gemini provides clear and well-formatted answers, but may lack technical detail or strict adherence to prompt constraints.

Perplexity is outstanding in factual search and citation, provides immediate results, but sacrifices conversational depth and creative reasoning.

Google AI (Gemini or Bard lineage) benefits from Google's ecosystem integration, handling multimodal and long-context queries well but sometimes leans towards generic summaries.

Meta ranks average across criteria, occasionally lagging in technical nuance and output depth.


## Result
Each platform excels in specific areas, as outlined. ChatGPT is best for detailed reasoning, Gemini for integration and context, Perplexity for fact-checking speed, Google AI for daily summaries, and Meta for basic responses.

