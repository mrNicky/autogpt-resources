# 🤖 AutoGPT - AI-Powered Workflow System
AutoGPT is an AI-driven system designed to enhance user interactions and streamline workflows using OpenAI's ChatGPT.

Silicon Valley's latest fascination is Auto-GPT, an open-source app that leverages OpenAI's AI models, GPT-3.5 and GPT-4, to autonomously perform tasks. It interacts with online and local software, handling follow-up interactions with the AI models until a task is complete. Auto-GPT's popularity stems from its ability to engage with various applications and services, like creating basic websites and devising marketing strategies.


## 📋 Workflow Overview


<p align="center">
  <img src="https://user-images.githubusercontent.com/39512726/234097856-40217e13-93b5-4a62-901c-7d21dc6e7033.png" alt="auto_gpt">
</p>
 

1. **👤 User Input**: Users provide a name for their AI agent and set up to 5 goals in the terminal.
2. **📥 Initial Prompt**: An initial prompt based on user input is sent to the ChatGPT API, including instructions and commands.
3. **🗨️ ChatGPT Response**: ChatGPT returns a JSON string with its thoughts, reasoning, plan, criticism, and the next command.
4. **⚙️ Command Execution**: The system extracts and executes the command, returning a string value (e.g., search results or summaries).
5. **🧠 Memory Update**: ChatGPT's output and the command return string are combined and added to the system's memory.
6. **🔍 Short-Term Memory**: The context is stored as text in the short-term memory using a queue or FIFO data structure.
7. **📚 Long-Term Memory**: The context is also stored in long-term memory as (vector, text) pairs, searchable using KNN or approximate-KNN.
8. **💡 Relevant Memories**: The system queries long-term memory to retrieve the top-K most relevant memories based on short-term memory context.
9. **🔄 New Prompt**: A new prompt is created with the initial instructions, relevant memories, and an instruction to generate the next command.
10. **🔁 Loop**: The system repeats steps 3 to 10 until ChatGPT completes the task and issues the shut down command.


## AI agents have been gaining traction for the past four weeks, showcasing a wide range of remarkable advancements:

🌐 Rapid custom website creation

💻 SQL statement generation

📝 Task completion in to-do lists

🔍 Research and market analysis

💰 Sales prospect exploration

📈 Product and stock market data analysis

🤖 Python script creation and testing

🎙️ Podcast outline preparation

🎲 Support in RPG games

💪 Continuous self-improvement

Take a look at these specific projects:

## AutoGPT BuildInPublic

1. 🌐 Create a custom website in 3 minutes

   https://twitter.com/SullyOmarr/status/1644160222733406214

2. 💻 AutoGPT Intern: Understands database tables, writes SQL, and sends execution results to Slack

   https://twitter.com/KaranDoshi13/status/1647890397081788417

3. 📝 To-do list management: List tasks and let AutoGPT complete them

   https://twitter.com/thegarrettscott/status/1645918390413066240

4. 🔍 Specialized agents for research tasks

   https://twitter.com/dzhng/status/1648056958996606978

5. 🎙️ Agents that read the latest news and prepare podcast outlines

   https://twitter.com/jamesbbaker4/status/1645898646762782735

6. 💰 AI agents that independently perform sales prospecting using GPT-4

   https://twitter.com/ompemi/status/1645083062986846209

7. 🛍️ Product research assistance for your shopping needs

   https://twitter.com/LinusEkenstam/status/1646095934177124353

8. 📈 Stock market data analysis

   https://twitter.com/mohamed43840/status/1643913774372356098

9. 🧐 Market research conducting

   https://twitter.com/SullyOmarr/status/1645205292756418562

10. 🎮 Role-playing game (RPG) agents

    https://twitter.com/ChrisDzoba/status/1647417880626237441

11. 🤖 Code-writing agents

    https://twitter.com/FelipeSchieber/status/1647780395839111168

12. 🐍 Python script writing and execution, enabling debugging, development, and recursive self-improvement

    https://twitter.com/SigGravitas/status/1642181498278408193

13. 📁 Multi-file code creation: Write code to complete entire projects

    https://twitter.com/FelipeSchieber/status/1647780395839111168

14. 🧪 Code testing

    https://twitter.com/adamcohenhillel/status/1644836492294905856



## 🌐 Links

- [OpenAI's ChatGPT API](https://openai.com/api/)
- [OpenAI's ada-002 Embeddings API](https://example.com/ada-002)
- [Pinecone Vector Database](https://pinecone.io/)
 
