
# 🛍️ ShopAssist AI - GenAI Based Laptop Recommendation Chatbot

## 📌 Overview
**ShopAssist AI** is an interactive chatbot application powered by GenAI (LLMs) that recommends laptops based on user requirements. It combines conversational AI with rule-based filtering to enhance the online shopping experience for laptops.

## 🚀 Features
- Conversational chatbot interface for requirement gathering
- AI-driven understanding of user input
- Smart filtering from a structured laptop dataset
- Natural language explanation of top 3 laptop matches

## 🧠 Architecture
The application follows a 3-stage architecture:
1. **Requirement Extraction**: Collects user preferences via chat.
2. **Product Mapping & Filtering**: Filters laptops that match user needs.
3. **Product Recommendation**: Describes the top matching laptops in detail.



+------------------------+
|   User Interaction     |
| (User inputs needs via|
|      chatbot UI)       |
+----------+-------------+
           |
           v
+------------------------+
|  Stage 1: Requirement  |
|     Extraction         |
| (LLM/chatbot gathers   |
| detailed user input)   |
+----------+-------------+
           |
           v
+------------------------+
|  Stage 2: Product      |
| Mapping & Filtering    |
| (Compare user specs    |
| with product dataset,  |
| extract top matches)   |
+----------+-------------+
           |
           v
+------------------------+
|  Stage 3: Recommendation|
| (Explain top 3 laptops |
| to user in natural     |
| language)              |
+----------+-------------+
           |
           v
+------------------------+
|  Final Output to User  |
| (Interactive chat      |
| with recommended       |
| laptops)               |
+------------------------+
