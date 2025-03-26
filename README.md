# RAG ChatBot with AWS

Welcome to the **RAG ChatBot** project! This repository contains the documentation for building a chatbot using AWS services, designed to enhance workplace efficiency and knowledge management.

## Why Use This Model?

This RAG_CHATbot is designed to help companies streamline their information retrieval processes and improve overall efficiency. By leveraging this model, organizations can:
- **Enhance Customer Support**: Provide instant, accurate answers to customer queries, reducing response times and improving customer satisfaction.
- **Boost Internal Knowledge Management**: Enable employees to quickly find information, reducing the time spent searching for documents and increasing productivity.
- **Facilitate Training and Onboarding**: Assist new employees in learning about company policies, procedures, and resources through interactive chatbot sessions.
- **Support Sales and Marketing**: Equip sales teams with quick access to product information, pricing, and promotional materials, enhancing their ability to respond to client inquiries.

## Overview

This chatbot leverages AWS Lex for conversational interfaces, AWS Bedrock as the knowledge base, and AWS S3 for storing company documents. 
The chatbot is designed to provide quick and accurate responses to user queries by accessing a vast repository of company knowledge.

## Features

- **Conversational Interface**: Built with AWS Lex to handle natural language processing and user interactions.
- **Knowledge Base**: Utilizes AWS Bedrock to store and retrieve information, ensuring accurate and comprehensive responses.
- **Document Storage**: AWS S3 is used to store and manage company documents, making them easily accessible to the chatbot.

## Architecture Diagram

![image](https://github.com/user-attachments/assets/29511ca7-e77c-4367-8a28-c5162299f479)
- **Customer Support**: Provide instant answers to customer queries by accessing a knowledge base of FAQs and support documents.
- **Internal Knowledge Management**: Assist employees in finding information quickly, improving productivity and reducing the time spent searching for documents.
- **Training and Onboarding**: Help new employees learn about company policies, procedures, and resources by interacting with the chatbot.
- **Sales and Marketing**: Equip sales teams with quick access to product information, pricing, and promotional materials.

## Getting Started

1. **Set up AWS Lex**: Create a Lex bot and configure intents and slots to handle user queries.
2. **Configure AWS Bedrock**: Set up the knowledge base with relevant company information and documents.
3. **Store Documents in AWS S3**: Upload company documents to S3 and configure access permissions.
4. **Integrate Services**: Connect Lex, Bedrock, and S3 to enable seamless interaction and information retrieval.
