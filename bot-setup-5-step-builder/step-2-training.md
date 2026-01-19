# Step 2: Training

In the **Training** tab, you define what your chatbot actually knows. This is where you add the **knowledge base**.

### Training Your Chatbot&#x20;

Training is the process of adding knowledge to your chatbot so it can answer questions based upon that information. In Step 2 of chatbot creation, you provide your chatbot with content from various sources that it will learn from and use to respond to user queries.

#### Training Data Options

Your chatbot can learn from five different types of content sources:

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

***

**1. Add Document**

<figure><img src="../.gitbook/assets/image (56).png" alt="" width="249"><figcaption></figcaption></figure>

**What it is**: Upload files containing information you want your chatbot to learn from.

**Supported file formats**:

* PDF files (.pdf)
* Text files (.txt)
* Markdown files (.md)

**File size limit**: Maximum 10MB per file

**How to use**:

1. Click "Add Data" → "Add Document"
2. Either drag and drop your file into the upload area, or click "Browse File" to select a file
3. Wait for the upload to complete (you'll see a progress bar)
4. The document will be processed automatically
5. Once processing is complete, the document will appear in your knowledge base

**Best for**:

* Product manuals and documentation
* Company policies and procedures
* Training materials
* Any structured text content you have in file format

**Tips**:

* Make sure your documents are well-formatted and readable
* Break large documents into smaller, focused files for better results

***

**2. Add URL**

<div data-full-width="false"><figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div>

**What it is**: Extract content from web pages to train your chatbot. You can either scrape a single page or crawl multiple pages from a website.

**2 options available**:

**Option A: Crawl Website**

* **What it does**: Discovers and crawls all important pages from your website
* **How it works**:
  1. Enter your website URL (e.g., https://example.com)
  2. The system analyzes your site and finds all linked pages
  3. You'll see a list of discovered pages
  4. Select up to 10 pages at single time you want to train your chatbot with
  5. Click "Save" to process the selected pages

**Option B: Scrape Single Page**

* **What it does**: Extracts content from only the specific URL you provide
* **How it works**:
  1. Select "Scrape single page" option
  2. Enter the exact URL you want to scrape
  3. Click "Add"
  4. The page content is automatically extracted and processed

**Best for**:

* Your company website
* Blog posts and articles
* Product pages
* Help documentation pages
* Any publicly accessible web content

**Tips**:

* Make sure the URLs are publicly accessible (not behind login)
* For crawling, start with your homepage URL
* You can resync URLs later if content changes (available on Essential and Business plans)

***

**3. Add Text**

<figure><img src="../.gitbook/assets/image (58).png" alt="" width="249"><figcaption></figcaption></figure>

**What it is**: Manually add custom text content directly to your chatbot's knowledge base.

**How to use**:

1. Click "Add Data" → "Add Text"
2. Enter a title for your text content (e.g., "Company Overview", "Product Features")
3. Type or paste your text content in the text area
4. Click "Add" to save
5. The text will be processed and added to your knowledge base

**Best for**:

* Custom information not available in documents or on websites
* Company-specific details
* Product descriptions
* Frequently asked questions
* Any text content you want to add directly

**Tips**:

* Use descriptive titles to organize your content
* Break long text into multiple entries for better organization
* Keep text focused and relevant to what users might ask

***

**4. Questions with Answers (Q\&A)**

<div align="center"><figure><img src="../.gitbook/assets/image (59).png" alt="" width="250"><figcaption></figcaption></figure></div>

**What it is**: Create structured question-and-answer pairs that your chatbot will use to respond to specific questions.

**How to use**:

1. Click "Add Data" → "Questions with Answers"
2. Enter a title for your Q\&A set (e.g., "Product FAQs", "Support Questions")
3. Add question-and-answer pairs:
   * **Question**: The question users might ask
   * **Answer**: The exact answer you want your chatbot to provide
4. Click "Add" to save
5. The Q\&A pairs will be processed and added to your knowledge base

**Best for**:

* Frequently asked questions (FAQs)
* Common support questions
* Product-specific questions
* Any questions where you want exact, controlled answers

**Tips**:

* Write questions as users would naturally ask them
* Provide clear, complete answers
* Review and update Q\&As regularly as your business evolves

***

**5. WordPress Content**

<div><figure><img src="../.gitbook/assets/image (63).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/image (62).png" alt="" width="375"><figcaption></figcaption></figure></div>

**What it is**: Import content directly from your WordPress website, including posts, pages, and custom post types.

**How to use**:

1. Click "Add Data" → "WordPress Content"
2. If you have WordPress sites connected, select the site you want to import from
3. Choose the post type (Posts, Pages, or custom post types)
4. Browse and select the specific posts or pages you want to import
5. Click "Add Content" to process
6. The selected WordPress content will be imported and added to your knowledge base

**Best for**:

* WordPress website owners
* Blog posts and articles
* Any content hosted on WordPress

**Requirements**:

* Your WordPress site must be connected to AI Botkit
