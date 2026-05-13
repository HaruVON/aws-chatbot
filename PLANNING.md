# AWS Chatbot Planning
---

A LLM chatbot that interacts with AWS and is able to answer questions about the different accounts

## Deliverables
---

- [ ] Code
- [ ] README
- [ ] requirements.txt
- [ ] Sample output in a zip file
 
## Requirements
---

- [ ] Create a natural language chatbot via Python's Langchain
- [ ] Interface it with AWS
- [ ] Must be able to add various AWS APIs in the form of Langchain's custom tools
- [ ] Must be able to answer question's such as:
    1. How many S3 buckets are exposed to the public?
    2. What data does the S3 bucket <insert the name of an S3 bucket that has a few files here> hold?
    3. What is the size of the EC2 instance with IP <insert the IP of an EC2 instance in your test account here>?
    4. What permissions does the user <insert an IAM user in the account here> have?

### Personal Requirement
---

- [ ] Must have extensive testing
- [ ] Would be nice to have a frontend (Streamlit?)
- [ ] Dockerized
    - [ ] Different build steps
- [ ] Docker Compose
    - [ ] Different production stacks
- [ ] Dynamic configuration for different llm models (defaults to a local ollama instance via docker)
- [ ] Logging and showcase alerting

### Tech Stack
---

- Backend
    - Python
        - Langchain (LLM Connection)
        - LangServe (API Backend)
        - LangSmith (Observability and Testing)
        - Moto
        - AWS SDK for Python (Boto3)
- Frontend
    - Python?
        - Streamlit
    - ReactJS?
        - assistant-ui
- Ollama
- AWS
- Docker
    - Docker Compose
    - Healthchecks
    - Buildstages
    - 