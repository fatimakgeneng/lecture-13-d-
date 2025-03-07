# Wroking of multiple agents using multiple LLMs

Here **DeepSeek** (installed locally via Ollama) and **Gemini** (using API from AI Studio) has been used.

You only need to add the following in either the dev_crew.py file or,

```llm1=LLM(model='ollama/deepseek-r1:1.5b', base_url="http://localhost:11434")
llm2=LLM("gemini/gemini-2.0-flash")
```

agents.yaml file (syntax is slightly different in yaml).
