# Setting up API keys for LLM

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

### <mark style="color:blue;">Setting Up OpenAI (Recommended for Beginners)</mark>

#### Step 1: Create Your OpenAI Account

1. Go to [https://platform.openai.com](https://platform.openai.com)
2. Click **"Sign up"** and create your account
3. Verify your email address
4. Add your phone number for verification

#### Step 2: Add Payment Method

1. Once logged in, go to **"Billing"** in the left sidebar
2. Click **"Add payment method"**
3. Add your credit card (don't worry - you won't be charged much!)
4. Set a **spending limit** (start with $5-10 for testing)

#### Step 3: Create Your API Key

1. Go to **"API Keys"** in the left sidebar
2. Click **"Create new secret key"**
3. Give it a name like "My Website Chatbot"
4. **Important:** Copy the key immediately! You won't be able to see it again
5. It will look like: `sk-proj-abc123...` (keep this safe!)



🎉Congratulations !! You now have your own OpenAI API Key.



<div align="center" data-full-width="true"><figure><img src="../.gitbook/assets/image (16).png" alt="" width="375"><figcaption></figcaption></figure></div>

### <mark style="color:blue;">Setting Up Anthropic (Claude)</mark>

#### Step 1: Create Your Anthropic Account

1. Go to [https://console.anthropic.com](https://console.anthropic.com)
2. Click **"Sign Up"** and create your account
3. Verify your email address

#### Step 2: Add Credits

1. In the console, go to **"Credits"**
2. Click **"Purchase credits"**
3. Start with $5 in credits for testing

#### Step 3: Generate API Key

1. Go to **"API Keys"** in the left menu
2. Click **"Create Key"**
3. Give it a name like "Website Chatbot"
4. Copy the key (it starts with `sk-ant-...`)

#### Step 4: Get VoyageAI Key (For Embeddings)

Anthropic uses VoyageAI for embeddings (understanding document content):

1. Go to [https://dash.voyageai.com](https://dash.voyageai.com)
2. Sign up and verify your account
3. Go to **"API Keys"** and create a new key
4. Copy this key too

#### Step 5: Configure in AI BotKit

1. In WordPress admin, go to **AI BotKit > Settings**
2. Select **"Anthropic"** from the AI Engine dropdown
3. Enter your **Anthropic API Key**
4. Enter your **VoyageAI API Key**
5. Click **"Verify"** to test both connections
6. Click **"Save Changes"**

***

<figure><img src="../.gitbook/assets/image (17).png" alt="" width="375"><figcaption></figcaption></figure>

### <mark style="color:blue;">Setting Up Google AI</mark>&#x20;

#### Step 1: Get Google AI Studio Access

1. Go to [https://makersuite.google.com](https://makersuite.google.com)
2. Sign in with your Google account
3. Accept the terms of service

#### Step 2: Create API Key

1. Click **"Get API Key"** in the left sidebar
2. Click **"Create API Key"**
3. Select your Google Cloud project (or create a new one)
4. Copy the generated API key

#### Step 3: Configure in AI BotKit

1. In WordPress admin, go to **AI BotKit > Settings**
2. Select **"Google"** from the AI Engine dropdown
3. Enter your **Google API Key**
4. Click **"Verify"** to test the connection
5. Click **"Save Changes"**
