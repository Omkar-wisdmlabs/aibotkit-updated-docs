# Step 4 - Model Config

### <mark style="color:blue;">Step 4: Model Configuration</mark> ⚙️

_Fine-tuning your AI's performance_

#### **Understanding AI Models:**

Think of this like choosing the "brain power" for your chatbot. More powerful models give better answers but cost more per conversation.



**🧠 AI Model Selection**

**Select from the available models given by your AI provider:**



**Setting the Parameters :**&#x20;

**💬 Max Messages (Default: 5)**

* **What it controls:** How much chat history the AI remembers
* **Higher numbers:** Better context understanding, higher costs
* **Lower numbers:** Less context, lower costs
* **Sweet spot:** 3-7 messages for most use cases



**📄 Max Context Chunks (Default: 3)**

* **What it controls:** How many knowledge base documents the AI can reference per response
* **Higher numbers:** More comprehensive answers, higher costs
* **Lower numbers:** Focused answers, lower costs
* **Sweet spot:** 2-5 chunks for most use cases



**🔤 Max Tokens (Default: 1000)**

* **What it controls:** Maximum length of AI responses
* **1000 tokens ≈ 750 words**
* **Recommendations:**
  * **Short answers:** 500 tokens
  * **Detailed responses:** 1000-1500 tokens
  * **Very detailed:** 2000+ tokens

#### **💰 Cost Optimization Tips:**

1. **Start conservative:** Use default settings initially
2. **Monitor usage:** Check your AI provider's usage dashboard
3. **Adjust based on needs:** Increase limits only if responses are too short/limited
4. **Test thoroughly:** Higher settings = higher costs per conversation



#### **✅ Step 4 Checklist:**

* [ ] Select appropriate AI model for your use case
* [ ] Set conversation memory (3-7 messages recommended)
* [ ] Configure context chunks (2-5 recommended)
* [ ] Set response length (500-1500 tokens recommended)
