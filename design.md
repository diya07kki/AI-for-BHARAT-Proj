# System Design
Grameen Sathi AI

# PLANNED ARCHITECTURE OVERVIEW
Grameen Sathi AI will use a simple , user friendly three layer architecture model : 
A mobile frontend , a cloud based back-end  and an AI layer powered by an LLM through Amazon Bedrock.

# WORKFLOW
User Input  -> AI Assistant -> Output
The user asks questions through voice or text. The AI responds with simple step-by-step guidance on their queries.


# TECH STACK

## Frontend (AI CHATBOT)
Native Android(Kotlin) for cross-platform support.
Simple UI with voice input support.

## Backend (Cloud-Based)
AWS Lambda for serverless backend logic.
Amazon API Gateway to handle app requests.
Amazon S3 for storage of documents and resources.

## AI Layer
Amazon Bedrock for Large Language Model (LLM).
AI chatbot for guidance and Q&A.

## Database (Planned)
Amazon DynamoDB for storing FAQs and user data.

## Language Support
Amazon Translate for regional languages.


# DATA USAGE
Amazon seller guidelines and help resources.
General pricing trends from e-commerce platforms.
Product category information.
Language translation datasets for regional support.
No personal or sensitive user data is required in the initial version.

# USER INTERFACE
Voice-based interaction for low literacy users.
Support for regional languages.
Large buttons and clear icons.
Minimal text and easy navigation.

# FUTURE SCOPES
Store user preferences as confidential data to improve personalization.
Directly integrated into Amazon's website as an AI chatbot to guide rural sellers in real time.
Scaled and offered to other e-commerce platforms, enabling cross-platform seller support.
