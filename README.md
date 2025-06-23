# functiontools_openaiagentsdk

# 🤖 OpenAI Agents SDK Example: Weather Tool with Agent Loop

This project demonstrates a beginner-friendly usage of the OpenAI Agents SDK using a synchronous agent (`run_sync`). The agent uses a tool called `weather_tool` to respond to weather-related queries by calling a custom function.

## 🚀 What’s Inside?

- **LLM:** Google Gemini Flash (`gemini/gemini-2.0-flash`)
- **Agent Loop:** Basic agent using `Runner.run_sync`
- **Tools:** Custom weather lookup function
- **SDK:** [`openai_agents`](https://openai.github.io/openai-agents-python/)
- **Model integration:** Using LiteLLM to connect Gemini

## 🧠 Concepts Covered

- Agent creation
- Tool registration using `@function_tool`
- Running agents with `Runner.run_sync`
- Integrating Gemini model via LiteLLM
- Google Colab support with `nest_asyncio`

## 🔧 How to Run

```bash
pip install -U openai_agents "openai_agents[litellm]"
