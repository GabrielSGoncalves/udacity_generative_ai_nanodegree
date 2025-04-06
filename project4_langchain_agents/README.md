# Project 4: Langchain Real State
## Overview
The goal of this project is building a customized AI Agent called "HomeMatch" for helping customers searching for real state available on a synthetic database.

HomeMatch is an innovative application designed to revolutionize the real estate search process by creating personalized property listings tailored to individual buyer preferences. Leveraging Large Language Models (LLMs) and vector databases, HomeMatch transforms standard real estate listings into engaging narratives that resonate with buyers' unique needs and lifestyles.

## Getting Started
### Prerequisites
- Python 3.10
- uv
- OpenAI API key


### Installation Steps
With `uv` and Python Python 3.10 installed, create and local environment with the needed dependencies with:
```bash
uv python install 3.10
uv venv
uv sync
```

Make sure you have a `.env` file in this folder with your OpenAI API key using the template below:
```
OPENAI_API_KEY="voc-123456789012345678901234567890123456.12345678"
```

Finally, open the Jupyter Lab and execute the project notebook from start to end.
```
uv run jupyter lab
```

## References
- [uv deep dive](https://www.saaspegasus.com/guides/uv-deep-dive/)
- [uv Documentation](https://docs.astral.sh/uv/)
- [Langchain Docs](https://python.langchain.com/docs/tutorials/)
- [LanceDB Docs](https://lancedb.github.io/lancedb/)