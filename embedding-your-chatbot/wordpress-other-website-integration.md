# WordPress / Other Website Integration

For WordPress, AI Bot Kit offers two ways to embed your chatbot: using the **Custom HTML block** or the **AI Bot Kit plugin**.

***

#### Option A: Using a Custom HTML Block

1. Go to your WordPress dashboard.
2. Open the page or post where you want the chatbot.
3. Click **+ Add Block** and select **Custom HTML**.
4. Paste the AI Bot Kit embed code:

```html
<div id="ai-bot-kit-chatbot" data-chatbot-id="XXXXXXXX"></div>
<script src="https://app.aibotkit.io/embed.js" async defer></script>
```

5. Update or Publish the page.

The chatbot will now be visible on that specific page.

***

#### Option B: Using the AI Bot Kit Plugin

For a simpler, site-wide installation:

1. Download the **AI Bot Kit WordPress Plugin** from your dashboard.
2. Log into WordPress → **Plugins → Add New → Upload Plugin**.
3. Upload the `.zip` file, install, and click **Activate**.
4. Go to **AI Bot Kit Settings** inside your WP Admin.
5. Enter your chatbot ID (available in your AI Bot Kit dashboard).
6. Save changes.

That’s it! Your chatbot will now run automatically across your entire WordPress site.

***

#### Pro Tips

* Use **Custom HTML** if you want the chatbot on a specific landing page only.
* Use the **Plugin** if you want it to show everywhere (site-wide).
* If the chatbot doesn’t appear immediately, clear your WordPress cache or CDN.

📘 Full guide available here:\
[👉 How to Add AI Bot Kit Chatbot to WordPress](https://aibotkit.io/blogs/wordpress-chatbot/)
