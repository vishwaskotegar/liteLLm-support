# Log

## Day 1 - Sep 30

Goal: repo + deps + first commit
Versions: langchain==1.4.3, chromadb==1.5.9, ragas==0.4.3, fastapi==0.142.1
Done: project repo created
Broke: python 3.14 is incompatible with a few packages like ragas so chose python 3.12 which is stable enough.
Tomorrow: download LiteLLM docs into data/docs

## Day 2 - Sep 30

Goal: get LiteLLM docs into data/docs
Source: github.com/BerriAI/litellm-docs (docs moved out of the main litellm repo)
File count: 837 (dir data\docs /s /b | find /c ".md")
Done: docs copied
Broke: first looked in the main litellm repo, docs folder no longer exists there
Tomorrow: pull closed GitHub issues via the API
