# Adding Knowledge (RAG)

## 📚 Building Your Knowledge Base

### <mark style="color:blue;">What is a Knowledge Base?</mark>

Think of your Knowledge Base as your chatbot's "brain food" - it's all the information you feed to your AI assistant so it can answer questions intelligently about your business, products, services, or any topic you want it to know about.

**Why is this important?** Without a knowledge base, your chatbot can only provide generic answers. With a well-built knowledge base, it becomes a smart assistant that knows everything about YOUR specific business and content.

***

### <mark style="color:blue;">3 Ways to Add Knowledge</mark>

AI BotKit gives you **three simple ways** to build your chatbot's knowledge base:



<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption><p>KB</p></figcaption></figure>

#### [📄 **1. Upload Documents**](upload-document.md)

#### [🌐 **2. Add Website URLs**](add-url.md)

#### [📝 **3. Import from WordPress**](import-from-wp.md)

***

### <mark style="color:blue;">Managing Your Knowledge Base</mark>

#### **Knowledge Base Dashboard Overview:**



<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

When you open your Knowledge Base, you'll see:

#### 📈 Statistics Card

* **Total Resources**: Count of all items
* **URLs**: Number of web pages added
* **Documents**: Number of files uploaded
* **WordPress Posts**: Imported from your site

***

#### 📑 Content Tabs

* **All Resources**: Unified view
* **Documents**: Uploaded files
* **URLs**: Web pages

***

#### 🔍 Search & Filter

* **Search** all content
* **Filter** by type
* **Sort** by date added

#### **Content Status Explained:**

| Status            | What It Means                               | What To Do                                          |
| ----------------- | ------------------------------------------- | --------------------------------------------------- |
| **🟡 Pending**    | Waiting to be processed                     | Wait - processing starts automatically              |
| **🔵 Processing** | AI is reading and understanding the content | Wait - usually takes 1-5 minutes                    |
| **✅ Completed**   | Ready to use in your chatbot                | Nothing - your chatbot can now use this information |
| **❌ Failed**      | Something went wrong                        | Try uploading again or check the file/URL           |

***

### 🔧 <mark style="color:blue;">Troubleshooting Common Issues</mark>

#### **❌ "File upload failed"**

* **Check file size:** Must be under 10 MB
* **Check file format:** Only PDF format is supported currently
* **Try again:** Sometimes temporary server issues occur

#### **❌ "URL is not accessible"**

* **Check the URL:** Make sure it's complete and correct
* **Check if it's public:** URL must be publicly accessible (no login required)
* **Wait and retry:** Sometimes websites are temporarily down

#### **❌ "Processing failed"**

* **File quality:** Ensure PDF has readable text (not just images)
* **Content length:** Very short content might not process well
* **Try re-uploading:** Sometimes processing fails temporarily

#### **❌ "No content found in WordPress"**

* **Check privacy settings:** Content must be published (not draft)
* **Verify post types:** Make sure the content type is selected
* **Check date filters:** Adjust date range if using filters

***

### 🎉 Your Knowledge Base is Ready!

Once you've added content using any of these methods, your AI chatbot will be able to:

* Answer questions about your specific business
* Reference your website content
* Give personalized responses based on your knowledge

**Remember:** The better your knowledge base, the smarter your chatbot becomes! Start with your most important content and gradually expand from there.

***

### 🔄 Next Steps

#### [Configure Your LLM](../configure-llm/)

