## IntelliFoods: Smart Recipe Recommendations and Ingredient Substitutions

IntelliFoods is an AI-powered kitchen companion that offers two key functionalities:
1. **Smart Recipe Recommendations**: Analyzes your available ingredients and suggests possible recipes you can make right now
2. **Intelligent Substitutions**: When you're missing an ingredient, it recommends suitable substitutions based on what you have, making recipes more accessible

The system takes into account ingredient expiry dates, helping users prioritize ingredients that need to be used soon, thereby reducing food waste.

Our recipe recommendation system leverages three key AI components:

1. **AI21-Jamba-1.5-Mini LLM**: Integrated via LangChain for natural language understanding and generation, specifically for analyzing recipe requests and generating ingredient substitution suggestions.
2. **Amazon Bedrock Knowledge Base**: Stores and processes recipe information, allowing for intelligent retrieval and contextualization of recipe data based on user ingredients.
3. **MongoDB Atlas Vector Search**: Enables semantic similarity matching between user ingredients and recipes using vector embeddings, ensuring accurate recipe recommendations based on available ingredients.

These components work together through LangChain's RAG framework to provide intelligent recipe recommendations and ingredient substitutions based on users' available ingredients.

we have two repo in this organization:
1. `intellifoods_backend` is the backend repo for this system
2. `intelli-foods` is the frontend repo for this system

visit the repos to get more details for how our system work. 

We also deployed our system already. Please do visit our website to play around with it. 

live URL: https://intelli-foods.vercel.app/ 

This repo is meant for MongoDB AI Hackathon: Code for a Cause.

created by:
@shaunliew
@elz-ming
