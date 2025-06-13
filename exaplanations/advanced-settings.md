# Advanced Settings

## ⚙️ <mark style="color:blue;">Advanced Settings Guide</mark>

### What Are Advanced Settings?

Once you've set up your API keys, AI BotKit offers several advanced settings that control how your chatbot processes content and interacts with users. Think of these as the "fine-tuning knobs" that help you optimize your chatbot's performance and behavior.

**💡 Good News:** The default settings work well for most websites! You only need to adjust these if you have specific requirements or want to optimize performance.

***

### 🧠<mark style="color:blue;">Embedding Models</mark>

**Embedding models** are AI tools that turn **text (or other data)** into **numbers** — specifically, **vectors** — so that computers can understand and compare their meanings.

#### 📦 Imagine This:

You give the model a sentence like:

> “How’s the weather today?”

The model turns it into a list of numbers like:

> `[0.45, -0.13, 0.88, ...]`

This list of numbers is called an **embedding**. Similar sentences will have **similar embeddings**.

***

#### 🔍 Why Is This Useful?

Embedding models help with tasks like:

* **Search**: Find content that's similar in meaning (even if it's not the same words).
* **Recommendations**: Show related articles, documents, or products.
* **Clustering**: Group similar ideas together.
* **Chatbots & AI Assistants**: Understand and match user questions to the right answers.

***

#### 🛠️ Real-World Example:

If someone types:

> “Tell me a joke”

And your knowledge base has a document that says:

> “Here’s a funny story…”

The embedding model can tell those two are **close in meaning** — even if they use different words — and show the right content.

***

### 📄 <mark style="color:blue;">Chunk Size</mark>

#### What It Does:

When AI BotKit processes your documents, it breaks them into smaller pieces called "chunks." Think of it like cutting a book into chapters - each chunk contains related information that the AI can understand and reference.

#### How It Works:

* **Larger chunks** = More context, but fewer total chunks
* **Smaller chunks** = More precise targeting, but less context per chunk

#### Default Setting:

**1000 characters** (roughly 150-200 words)

#### Range:

* **Minimum:** 100 characters
* **Maximum:** 2000 characters

#### When To Adjust:

**Increase Chunk Size (1200-1500) When:**

✅ **Your content has long explanations** (tutorials, detailed guides)\
✅ **You want more context in answers**\
✅ **Your documents have complex, interconnected topics**\
✅ **You're getting fragmented or incomplete answers**

**Decrease Chunk Size (600-800) When:**

✅ **Your content is mostly short FAQs**\
✅ **You want more precise, focused answers**\
✅ **Your documents have many separate topics**\
✅ **You're getting overly long or unfocused answers**

#### Real-World Examples:

**E-commerce Store (Recommend: 800-1000)**

* Product descriptions are usually concise
* Users ask specific questions about features

**Educational Site (Recommend: 1200-1500)**

* Content is detailed and explanatory
* Concepts build on each other

***

### 🔗 <mark style="color:blue;">Chunk Overlap</mark>

#### What It Does:

This setting ensures that important information doesn't get "lost" between chunks. It's like having overlapping sections in a book so you don't miss the connection between chapters.

#### How It Works:

* Takes the last X characters from one chunk
* Includes them at the beginning of the next chunk
* Ensures context continuity between chunks

#### Default Setting:

**200 characters** (roughly 30-40 words)

#### Range:

* **Minimum:** 0 characters (no overlap)
* **Maximum:** 200 characters (20% of default chunk size)

#### When To Adjust:

**Increase Overlap (300-400) When:**

✅ **Your content has lots of cross-references**\
✅ **Topics are highly interconnected**\
✅ **You're getting answers that miss important connections**\
✅ **Your content has step-by-step processes**

**Decrease Overlap (50-100) When:**

✅ **Your content is mostly independent sections**\
✅ **You want to reduce processing time**\
✅ **Your content has clear topic boundaries**\
✅ **Storage/cost optimization is important**

#### Impact on Performance:

* **More overlap** = Better context but higher processing costs
* **Less overlap** = Faster processing but potential context loss

***

### ⏱️ <mark style="color:blue;">Rate Limit Window</mark>

#### What It Does:

Controls the time period for counting API requests. Think of it as a "rolling window" that tracks how many requests users make.

**Simple Analogy:** Like having a timer that resets every X seconds to count fresh requests.

#### How It Works:

* Tracks requests made in the last X seconds
* When window expires, counter resets
* Prevents abuse and controls costs

#### Default Setting:

**60 seconds** (1 minute)

#### Range:

* **Minimum:** 1 second
* **Maximum:** 3600 seconds (1 hour)

#### When To Adjust:

**Increase Window (300-900 seconds) When:**

✅ **You want longer-term usage tracking**\
✅ **Your site has steady, consistent traffic**\
✅ **You prefer hourly rather than minute-based limits**\
✅ **You want to smooth out traffic spikes**

**Decrease Window (15-30 seconds) When:**

✅ **You want strict, immediate rate limiting**\
✅ **Your site gets sudden traffic bursts**\
✅ **You want to prevent rapid-fire requests**\
✅ **Cost control is critical**

***

### 🚦 <mark style="color:blue;">Rate Limit Max Requests</mark>

#### What It Does:

Sets the maximum number of chatbot requests allowed within the rate limit window. This is your primary tool for controlling usage and costs.

**Simple Analogy:** Like setting a speed limit - it determines how fast users can make requests.

#### Default Setting:

**60 requests** per window (1 request per second on average)

#### Range:

* **Minimum:** 1 request
* **Maximum:** 1000 requests

#### When To Adjust:

**Increase Limit (100-200) When:**

✅ **You have high-traffic periods**\
✅ **Multiple users chat simultaneously**\
✅ **You want to provide unlimited-feeling experience**\
✅ **Your AI budget is flexible**

**Decrease Limit (20-40) When:**

✅ **You want to control AI costs strictly**\
✅ **Your site has mostly single users**\
✅ **You're testing the chatbot initially**\
✅ **You want to prevent abuse**

#### Usage Scenarios:

**Small Blog (Recommend: 30-50 requests)**

* Few concurrent users
* Casual interaction patterns

**Business Website (Recommend: 60-100 requests)**

* Moderate traffic
* Standard business hours usage

**E-commerce Store (Recommend: 100-200 requests)**

* High traffic during sales
* Multiple customer service interactions

***

### 🎯 <mark style="color:blue;">Choosing The Right Settings For Your Site</mark>

#### 🛒 **E-commerce Product Catalog**

```
Chunk Size: 800-1000 characters
Chunk Overlap: 150-200 characters
Rate Limit Window: 60 seconds
Max Requests: 100-200
```

**Why:** Product info is concise, but you need to handle customer service spikes.



#### 💼 **Professional Services Site**

```
Chunk Size: 1000-1200 characters
Chunk Overlap: 200-250 characters
Rate Limit Window: 60 seconds
Max Requests: 40-80
```

**Why:** Professional content needs context, but traffic is usually moderate.

***

### 🚨 Troubleshooting Common Issues

<table data-header-hidden><thead><tr><th width="335">Issue</th><th>Solution</th></tr></thead><tbody><tr><td><mark style="background-color:blue;">Issues</mark></td><td><mark style="background-color:blue;">Solution</mark></td></tr><tr><td>Answers seem incomplete or cut off</td><td>Increase <strong>chunk size</strong> to 1200–1500 characters</td></tr><tr><td>Chatbot loses context between related topics</td><td>Increase <strong>chunk overlap</strong> to 250–300 characters</td></tr><tr><td>Users complain about rate limiting</td><td>Increase <strong>max requests</strong> or extend the <strong>rate limit window</strong></td></tr><tr><td>AI costs are too high</td><td>Decrease <strong>max requests</strong> and optimize <strong>chunk size</strong></td></tr><tr><td>Responses are too slow</td><td>Decrease <strong>chunk size</strong> and <strong>overlap</strong>; check <strong>rate limits</strong></td></tr><tr><td>Getting irrelevant answers</td><td>Decrease <strong>chunk size</strong> for more precise content targeting</td></tr></tbody></table>

***

### 📞 When To Seek Help

Contact support or consider professional setup if:

* Your costs are unexpectedly high despite optimization
* Users consistently report poor answer quality
* You're experiencing frequent rate limiting issues
* Your content has unique requirements not covered here

**Remember:** These settings can always be adjusted! Start with defaults, monitor performance, and fine-tune based on your specific needs and user feedback.

***
