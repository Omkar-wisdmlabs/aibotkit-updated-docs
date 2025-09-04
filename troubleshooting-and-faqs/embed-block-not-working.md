# Embed Block Not Working

If you’ve added the chatbot code to an **Embed Block** (Squarespace, WordPress, or other site builders) but it’s still not showing up, here are the common reasons and fixes.

***

#### 1. Check for Code Restrictions

* Some platforms sanitize or strip out certain `<script>` tags from Embed Blocks.
* If your builder doesn’t allow scripts inside normal embed blocks, move the code to:
  * **Footer Injection** (Settings → Advanced → Code Injection → Footer).
  * Or a **Custom HTML block** if supported.

***

#### 2. Ensure Full Code is Pasted

* Make sure you copied **both lines** of the AI Bot Kit code:

```html
<div id="ai-bot-kit-chatbot" data-chatbot-id="XXXXXXXX"></div>
<script src="https://app.aibotkit.io/embed.js" async defer></script>
```

* If you only paste the `<div>` without the `<script>`, the bot won’t load.

***

#### 3. Squarespace-Specific Issues

* Squarespace’s default **Embed Block** doesn’t always support `<script>` tags.
* Fix: Use **Code Injection** instead for site-wide installation.
  * Go to **Settings → Advanced → Code Injection → Footer**.
  * Paste the full AI Bot Kit code.
  * Save changes.

📘 See full guide: How to Add AI Bot Kit Chatbot to Squarespace

***

#### 4. WordPress-Specific Issues

* If you’re using the **Block Editor**, the “Embed” block is for iFrames only — it won’t run JavaScript.
* Fix: Use the **Custom HTML Block** instead.
  * Open your page/post → Add Block → Select **Custom HTML**.
  * Paste the code → Update.

📘 See full guide: How to Add AI Bot Kit Chatbot to WordPress

***

#### 5. Clear Cache and Refresh

* If you’ve placed the code correctly but still don’t see the bot:
  * Clear your site cache (if you’re using caching plugins or CDN).
  * Refresh in **Incognito Mode** to bypass browser cache.

***

#### 6. Alternative Fixes

* For Wix, Webflow, and Shopify: Always use **Custom Code** injection under site settings.
* For custom-coded websites: Add the snippet just before the closing `</body>` tag.

***

⚡ **Quick Recap:**

* Embed blocks often block scripts.
* Use **Code Injection** or **Custom HTML** blocks instead.
* Always paste the full code snippet.
