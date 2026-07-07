# Deprected. 

This repository is now deprecated. All issues with the Swiss AI models should be reported to:
 - As a community discussions for relevant models on HuggingFace for functional failures 
   - eg https://huggingface.co/swiss-ai/Apertus-70B-Instruct-2509/discussions for the Apertus v1.0 70B Instruct version
   - eg https://huggingface.co/swiss-ai/Apertus-8B-Instruct-2509/discussions for the Apertus v1.0 8B Instruct version
 - to security@apertus-ai.org for responsible disclosure of any safety- or security- critical applications
 - to privacy@apertus-ai.org for any questions regarding personal information.

# Apertus-Generation-Issues-Reports
This is the repository for reporting issues with the SwissAI Apertus Model family generation

If you encountered an issue with the output of the SwissAI Apertus family model not intendend for research (ie -Instruct), please fill the report as an Issue to this repository, providing:
- Full model name and version
- Deployment stack (API endpoint deployed by X, Transformers, vLLM), incuding the versions
- The prompt or prompt series required to reproduce the behaviour
- Generation parameters (if different from shipped)
- Obtained response
- Why the resulting response requires reporting

Please be aware of the inherent limitations of LLMs before reporting = notably thier incapability of generating factual information without reference factual data.
