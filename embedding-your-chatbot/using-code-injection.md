# Using Code Injection

Code Injection is the best method if you want your chatbot to **appear across every page of your website automatically**. Instead of adding the chatbot code block by block, you place it in the site-wide header or footer so it loads everywhere.

#### When to Use Code Injection

* You want the chatbot to appear on **all pages** without manually embedding.
* You’re using a website builder (Squarespace, Webflow, Shopify, Wix, etc.) that supports global code injection.
* You have direct access to your site’s **HTML, header, or footer files**.

***

#### How to Inject AI Bot Kit Code

1. Copy the embed code from your AI Bot Kit dashboard:

```html
<div id="ai-bot-kit-chatbot" data-chatbot-id="XXXXXXXX"></div>
<script src="https://app.aibotkit.io/embed.js" async defer></script>
```

2. Paste this code into your site’s **global header or footer** section.
   * Most website builders (Squarespace, Webflow, Wix, Shopify, etc.) provide a “Custom Code” or “Code Injection” option under **Settings → Advanced**.
   * If you’re editing your site manually, paste it before the closing `</body>` tag in your HTML template.
3. Save and republish your site.

***

#### Platform-Specific Notes

* **Squarespace**: Go to **Settings → Advanced → Code Injection → Footer**, paste the code, and save.
* **Webflow**: Go to **Project Settings → Custom Code → Footer Code**, paste the snippet, and publish.
* **Shopify**: Open **Online Store → Themes → Edit Code → theme.liquid**, and paste the code before `</body>`.
* **Wix**: Use **Settings → Advanced → Custom Code**, add your snippet, and set it to show on “All Pages.”

***

#### Pro Tips

* Place the code in the **footer** section rather than header whenever possible — it ensures faster page loading.
* If you’re using a caching plugin or CDN, clear the cache after adding the code.
* Test your chatbot on desktop and mobile to make sure the widget doesn’t overlap with other site elements.

***

⚡ **Why Use Code Injection?**

* **Site-wide coverage** → One paste = chatbot everywhere.
* **Cleaner setup** → No need to add blocks on individual pages.
* **Future-proof** → Any new pages you add will automatically have the chatbot.



***

👉 Now you’ll have 4 clean sections under **Embedding Your Chatbot**:

1. Getting Your Embed Code
2. Squarespace Integration
3. WordPress Integration
4. Code Injection
