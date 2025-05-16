
This project has recently been updated to include experimental support for the **OpenAI API**. The primary motivation behind this integration is to explore and test the capabilities of **Chain-of-Thought (CoT)** prompting techniques 

**⚠️ Important Notice:**
* The initial code for this OpenAI integration was partially generated with the assistance of **Cursor AI**.
* This feature is currently **under active testing and development**. Expect potential bugs or unexpected behavior. We appreciate your understanding and any feedback you can provide!


config your OpenAI key on bottom of /etc/cowrie.cfg.dist

[openai]
enabled = true
api_key =
model = gpt-3.5-turbo
system_prompt = You are a Linux command line interface. Respond as if you are the shell. Keep responses brief and realistic.
