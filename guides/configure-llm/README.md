# Configure LLM

## 🔑 Setting Up Your AI Provider&#x20;

### <mark style="color:blue;">API Keys</mark>

Think of API keys as your "membership cards" to use powerful AI services like OpenAI, Google, or Anthropic. These companies provide the intelligent "brains" that power your chatbot, but you need to have your own account and API key to access their services.

**Why do you need your own API key?**

* It ensures you have direct access to the latest AI models
* You only pay for what you use & have complete control over your AI usage

### 🎯 2 Step Setup Guide



<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

#### <mark style="color:blue;">Step 1: Choose Your AI Provider</mark>

AI BotKit supports three leading AI providers. You only need to set up **ONE** of them:

1. OpenAI ( [API setup](../../references/setting-up-api-keys-for-llm.md#setting-up-openai-recommended-for-beginners))
2. Claude by Anthropic ( [API Setup ](./#setting-up-anthropic-claude))
3. Gemini by Google ( [API Setup](./#setting-up-google-ai) )

**💡 Recommendation for beginners:** Start with **OpenAI** as it's the most popular and well-documented.

#### <mark style="color:blue;">Step 2 : Configuring AI Provider in AI BotKit</mark>

To set up your preferred AI engine:

1. **Go to your WordPress Admin Panel**
2. Navigate to **AI BotKit > Settings**
3. Select your AI engine from the **"AI Engine"** dropdown:
   * **OpenAI** (recommended for beginners)
   * **Anthropic (Claude)**
   * **Google AI**
4. Enter the required API key:
   * **OpenAI**: Paste your OpenAI API Key
     * _Optional_: Enter your **Organization ID** if applicable
   * **Anthropic (Claude)**:
     * Enter your **Anthropic API Key**
     * ➕ **Important**: Also enter your **VoyageAI API Key** (used for text embeddings)
   * **Google AI**: Enter your **Google API Key**
5. Click **"Verify"** to test the connection.
6. After successful verification, select your desired Chat Model and Embedding Model. \
   ( Learn more about Embedding Models [here ](../../exaplanations/advanced-settings.md#embedding-models))

***

### <mark style="color:blue;">AI Parameters</mark>&#x20;

**AI Parameters** are configurable settings that control how documents are processed and how often the LLM can be accessed.&#x20;

To change the default values, check out the [Advanced Settings](../../exaplanations/advanced-settings.md)

***

### <mark style="color:blue;">🚨 Troubleshooting Common Issues</mark>

#### "Invalid API Key" Error

* ✅ Double-check you copied the key correctly (no extra spaces)
* ✅ Make sure the key hasn't expired
* ✅ Verify you have credits/billing set up

#### "Rate Limit" Error

* ✅ You're making too many requests - wait a few minutes
* ✅ Check your provider's usage limits
* ✅ Consider upgrading your account tier

#### "Insufficient Credits" Error

* ✅ Add more credits to your AI provider account
* ✅ Check your spending limits

#### Connection Timeout

* ✅ Check your internet connection
* ✅ Try again in a few minutes
* ✅ Contact your hosting provider if issues persist

***

### 🔐 <mark style="color:blue;">Security Best Practices</mark>

#### Protecting Your API Keys:

✅ **Never share your API keys** with anyone\
✅ **Set spending limits** to avoid unexpected charges\
✅ **Regenerate keys** if you suspect they've been compromised\
✅ **Use different keys** for different projects\
✅ **Monitor usage** regularly in your provider dashboard

#### In AI BotKit:

* Your API keys are stored securely in WordPress
* They're encrypted and never displayed in plain text
* Only administrators can access them

***

### 🆘 <mark style="color:blue;">Need Help?</mark>

#### If You Get Stuck:

1. **Check the provider's documentation:**
   * [OpenAI Help Center](https://help.openai.com)
   * [Anthropic Support](https://support.anthropic.com)
   * [Google AI Studio Help](https://support.google.com/ai-studio)
2. **Verify your account setup:**
   * Confirm email verification
   * Check billing/credits
   * Review spending limits

***

**Congratulations!** You've just connected your website to cutting-edge AI technology! 🎉

### 🚀 What's Next?

Once your API keys are configured : Start Creating your own personalized Chatbot



