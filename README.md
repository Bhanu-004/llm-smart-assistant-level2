# 🤖 LLM Smart Assistant – Level 2

An AI-powered desktop chatbot built with **Python**, featuring:

-  Google Gemini LLM (Gemini 1.5)
-  Basic calculator tool for math queries
-  GUI built with Tkinter
-  Voice input and text-to-speech output
-  Interaction logging (`interaction_logs.txt`)

---

##  Description

This chatbot is designed as part of the **Level 2: Medium** tier of an LLM assistant challenge.

- It detects **math-related questions** and uses a custom calculator tool to answer them.
- It handles **general knowledge queries** using the Gemini LLM.
- It **logs all interactions** to a local text file.
- Voice input (🎤) and speech output (🔊) make the interaction hands-free and accessible.

>  Multi-intent queries like "Multiply 9 and 8 and also tell me the capital of Japan" are gracefully rejected, as per the level's constraints.

---


<img width="503" height="476" alt="lv21" src="https://github.com/user-attachments/assets/26db5694-a638-4cfe-a0f2-87fd316d8fd4" />




## 📂 File Structure

```plaintext
📁 
├── chatbot_with_tool.py         # Main chatbot app (GUI + logic)
├── calculator_tool.py           # Tool to parse and compute math expressions
├── interaction_logs.txt         # Stores all user-bot conversations
