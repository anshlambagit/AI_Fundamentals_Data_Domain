# AI Fundamentals for Data Domain

### Watch The Full Tutorial On YouTube
- https://youtu.be/kHq77-I1ZjE?si=jTGsQT4ZcX1Iijse

A comprehensive, hands-on course designed to teach the core concepts and practical applications of Artificial Intelligence in the data domain. From LLMs and embeddings to building AI agents, this course provides a structured path to mastering modern AI technologies.

## 🎯 What You'll Learn

This course covers the essential AI technologies transforming data science:

- **Large Language Models (LLMs)**: Understanding how modern AI language models work, accessing them via APIs, and generating rich text embeddings
- **Retrieval-Augmented Generation (RAG)**: Building intelligent systems that combine external knowledge with LLM capabilities for more accurate, context-aware responses
- **Prompt Engineering**: Mastering the art of crafting effective prompts to elicit desired outputs from language models
- **AI Agents**: Creating autonomous agents that can reason, plan, and use tools to solve complex problems (ReAct pattern, tool binding, memory management)

## 📚 Course Structure

### **Chapter 1: Large Language Models (LLMs)**
Master the fundamentals of modern language models and learn how to interact with them programmatically.

- `1_API_Calls.ipynb` - Making API calls to LLM providers and understanding model responses
- `2_Embeddings.ipynb` - Creating and working with text embeddings for semantic search and similarity tasks

**Key Concepts**: API authentication, prompt structure, token limits, embedding vectors, semantic similarity

---

### **Chapter 2: Retrieval-Augmented Generation (RAG)**
Learn how to augment LLMs with external knowledge bases for more accurate and grounded responses.

- `1_RAG.ipynb` - Building RAG systems from scratch
- **Tools**: ChromaDB for vector storage and retrieval
- **Dataset**: NovaS.pdf for demonstration

**Key Concepts**: Vector databases, semantic search, context windows, knowledge retrieval, hallucination reduction

---

### **Chapter 3: Prompt Engineering**
Develop advanced skills in crafting prompts that maximize LLM performance.

- `Prompting_Types.ipynb` - Exploring different prompting strategies (zero-shot, few-shot, chain-of-thought, role-playing)
- `prompt_call.ipynb` - Practical implementation of various prompt patterns

**Key Concepts**: Prompt templates, context injection, role-based prompting, multi-turn conversations

---

### **Chapter 4: Building AI Agents**
Create intelligent agents that can reason, plan, and take actions using tools.

- `1_Tool_Binding.ipynb` - Binding external tools and APIs to agents
- `2_ReAct_Agent.ipynb` - Building agents using the ReAct (Reasoning + Acting) pattern
- `3_Structured_Output.ipynb` - Extracting structured data from LLM responses
- `4_prompt_templates.ipynb` - Advanced prompt templating for agent orchestration
- `5.1_RAG_Semantic.ipynb` - Semantic search techniques for RAG systems
- `5.2_RAG_Agent.ipynb` - Combining RAG with agent capabilities
- `6_Agent_Memory.ipynb` - Implementing long-term and short-term memory for stateful agents

**Key Concepts**: Tool calling, agentic loops, reasoning chains, function calling, state management, multi-turn interactions

---

## 🚀 Quick Start

### Prerequisites
- **Python 3.11+**
- A code editor or IDE (VS Code, PyCharm, etc.)
- API keys for LLM providers (OpenAI, Anthropic, etc.)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd AI_Fundamentals
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # On Windows
   # or
   source .venv/bin/activate  # On macOS/Linux
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```
   OPENAI_API_KEY=your_api_key_here
   # Add other API keys as needed
   ```

5. **Start exploring**
   ```bash
   jupyter notebook
   ```
   Navigate to the chapter you want to explore and open the corresponding notebook.

---

## 📖 How to Use This Course

1. **Follow the chapters in order** (CH-1 → CH-4) to build foundational knowledge
2. **Run each notebook cell** and experiment with the code
3. **Modify examples** to deepen your understanding
4. **Work on the exercises** included in each notebook
5. **Build your own projects** using the patterns you've learned

**Estimated Time**: 40-60 hours for complete mastery (can be adjusted based on pace)

---

## 🛠️ Technologies & Libraries

- **OpenAI API** - LLM access and embeddings
- **ChromaDB** - Vector database for RAG
- **LangChain/LlamaIndex** - Agent and RAG frameworks
- **Jupyter** - Interactive notebook environment
- **Python 3.11+**

---

## 📁 Project Structure

```
AI_Fundamentals/
├── CH-1_LLMs/
│   ├── 1_API_Calls.ipynb
│   └── 2_Embeddings.ipynb
├── CH-2_RAG/
│   ├── 1_RAG.ipynb
│   ├── NovaS.pdf
│   └── chroma_db/
├── CH-3_Prompt_Engineering/
│   ├── prompt_call.ipynb
│   └── Prompting_Types.ipynb
├── CH-4_Agent/
│   ├── 1_Tool_Binding.ipynb
│   ├── 2_ReAct_Agent.ipynb
│   ├── 3_Structured_Output.ipynb
│   ├── 4_prompt_templates.ipynb
│   ├── 5.1_RAG_Semantic.ipynb
│   ├── 5.2_RAG_Agent.ipynb
│   ├── 6_Agent_Memory.ipynb
│   ├── chroma_db/
│   └── chroma_db_semantic/
├── main.py
├── requirements.txt
└── README.md
```

---

## 💡 Key Takeaways by Chapter

| Chapter | Core Skills | Practical Output |
|---------|------------|------------------|
| CH-1: LLMs | API integration, embeddings, vector operations | Text generation and semantic search |
| CH-2: RAG | Vector retrieval, prompt augmentation, context management | Knowledge-grounded AI responses |
| CH-3: Prompting | Prompt design, few-shot learning, reasoning patterns | Optimized interactions with LLMs |
| CH-4: Agents | Tool orchestration, agentic reasoning, memory systems | Autonomous AI agents solving complex tasks |

---

## 🎓 Learning Outcomes

After completing this course, you will be able to:
- ✅ Build applications powered by LLMs and embeddings
- ✅ Create RAG systems that leverage external knowledge
- ✅ Engineer prompts for optimal model performance
- ✅ Design and implement intelligent AI agents
- ✅ Handle advanced concepts like tool binding, memory, and reasoning

---

## 🤝 Contributing

Have improvements or additional content? Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request with your improvements

---

## 📝 License

This course material is provided for educational purposes.

---

## 📧 Feedback & Support

Have questions or suggestions? Open an issue on GitHub or reach out directly. Your feedback helps improve this course!

---

**Happy Learning! 🚀**

Get started with [Chapter 1: LLMs](CH-1_LLMs/) today.
