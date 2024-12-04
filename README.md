# RAG Chatbot Trained to Answer Questions on Water, Sanitation and Hygiene Services in Nigeria
A repository containing code that was used to train a RAG chatbot on WASH services in Nigeria.

### Files in Repo
The baseline.ipynb notebook is the initial naive RAG.
The qa_extraction.ipynb notebook contains the notebook where the question and answer pairs used as test data where extracted.
The raw_q_and_a folder contains the questions and answers in different levels before they were edited and compiled into the final 90 Q&A Pairs in test_data.pkl

### Introduction

There are numerous communities in Nigeria which do not have access to basic Water, Sanitation and Hygeine (WASH) Services. In a bid to mitigate this and work towards the UN's Sustainable Development Goal 6; "Clean Water and Sanitation for All" the Nigerian government collaborates with several stakeholders; multilateral and bilateral agencies, and NGOs. These organizations often need access to data about the existing facilities. Although the data exists from surveys conducted to catalogue that information and also in the form of reports, it is not easily accessible and accessing a specific piece of information that you are looking for quickly is not possible. 

This work uses Retrieval Augmented Generation (RAG) to leverage the power of Large Language Models (LLM) without the associated cost of fine-tuning or retraining the LLM to provide a Chatbot trained on the relevant WASH services data; so as to provide relevant information quickly without having to spend hours looking for the information. The LLM's pretraining will also enable it to not just provide the facts, but to also put them in context by providing extra explanation about the information it retrieved. RAG is a technique in which LLMs perform generation based on retrieved information that is relevant to the user query, this enriches the responses and makes LLMs useful in a knowledge-specific context. 
