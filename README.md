# AI Mood Board Generator

**AI Mood Board Generator** is a Flowise-based AI project that generates creative mood boards based on user-provided themes, keywords, and platforms. Using conversational AI and structured prompts, it produces visually-inspired ideas and content suggestions to help designers, marketers, and creatives visualize concepts efficiently.

---

## Features

- Generate mood boards based on **theme, keywords, and target platform**  
- Maintain context across multi-turn interactions using memory  
- AI-driven creative suggestions and concept generation  
- Structured output for easy integration into design tools or workflow automation  
- Flexible and interactive workflow for brainstorming and inspiration  

---

## Flowise Project Architecture

This project uses **six key Flowise nodes**:

1. **ChatOpenAI**  
   - Generates AI-powered creative suggestions for mood boards  

2. **Buffer Window Memory**  
   - Maintains context across multi-turn interactions  
   - Remembers previous prompts, keywords, and themes  

3. **LLMChain**  
   - Chains AI logic for sequential reasoning and processing user inputs  
   - Ensures consistent and structured output  

4. **Conversational Agent**  
   - Manages dialogue flow and handles multi-step queries  
   - Directs the AI on how to respond based on context  

5. **Prompt Template**  
   - Structures input prompts for ChatOpenAI  
   - Ensures outputs align with the selected **theme, keywords, and platform**  

6. **Structured Output Parser**  
   - Converts AI-generated ideas into structured JSON  
   - Makes data easy to programmatically use in applications or mood boards  

---

## How It Works

1. **User Inputs** → Provide **theme, keywords, and platform**  
2. **Prompt Template** → Formats these inputs for AI processing  
3. **LLMChain** → Sequentially processes the prompts  
4. **Conversational Agent** → Manages dialogue and reasoning flow  
5. **ChatOpenAI** → Generates creative ideas and mood board suggestions  
6. **Buffer Window Memory** → Maintains conversation and input context  
7. **Structured Output Parser** → Converts results into structured, usable data  

---

## Tech Stack

- **Flowise** – Node-based workflow orchestration  
- **OpenAI / ChatGPT** – AI-powered idea generation  
- **Prompt Engineering** – Ensures structured and consistent outputs  
- **Conversational Memory** – Maintains context across multi-turn prompts  
- **Structured Output Parser** – Converts AI outputs into JSON for workflow integration  

---

## Installation & Setup

1. **Clone the repository:**

```bash
git clone https://github.com/<your-username>/ai-mood-board-generator.git