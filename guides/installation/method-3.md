# Method 3

### <mark style="color:blue;"># 3: Manual Installation via FTP/File Manager</mark>

For advanced users who want full control over the installation process. 💪



**📁&#x20;**<mark style="color:blue;">**What You'll Need:**</mark>

* FTP client (like FileZilla) OR hosting file manager
* Your website's FTP credentials



**📝&#x20;**<mark style="color:blue;">**Step-by-Step Instructions**</mark>

**Step 1: Prepare the Plugin Files 📦**

1. Download the `ai-botkit.zip` file to your computer
2. **Extract/unzip** the file - you'll get a folder named `ai-botkit`
3. Keep this folder handy for uploading



**Step 2: Access Your Website Files 🌐**

_**Option A: Using FTP Client**_

1. Open your FTP client (FileZilla, WinSCP, etc.)
2. Connect using your FTP credentials
3. Navigate to your website's root directory
4. Go to `/wp-content/plugins/`



_**Option B: Using Hosting File Manager**_

1. Log into your hosting control panel (cPanel, Plesk, etc.)
2. Open **"File Manager"**
3. Navigate to `public_html/wp-content/plugins/`



**Step 3: Upload the Plugin 📤**

1. Upload the entire `ai-botkit` folder to `/wp-content/plugins/`
2.  Make sure the folder structure looks like:

    Copy

    ```
    /wp-content/plugins/ai-botkit/
    ├── ai-botkit.php
    ├── includes/
    ├── admin/
    ├── public/
    └── (other files...)
    ```



**Step 4: Set Proper Permissions 🔧**

Set these permissions (ask your hosting provider if unsure):

* **Folders**: 755 or 750
* **Files**: 644 or 640



**Step 5: Activate via WordPress ⚡**

1. Go to your WordPress admin panel
2. Navigate to **Plugins → Installed Plugins**
3. Find **"AI BotKit"** in the list
4. Click **"Activate"**



**⚠️ Manual Installation Tips:**

* **Double-check folder names** - case-sensitive on some servers
* **Verify file structure** - main plugin file should be directly accessible
* **Check permissions** - wrong permissions cause activation failures
* **Backup first** - always backup before manual installations



### 🎉 <mark style="color:blue;">Post-Installation Setup</mark>

Congratulations! AI BotKit is installed. Now let's get it configured! 🚀

#### **Immediate Next Steps:**

**1. Admin Details🧙‍ -**

After activating the plugin, a pop-up will appear prompting you to enter the admin's name and email address

<figure><img src="../../.gitbook/assets/image (6) (1).png" alt="Welcome pop-up image"><figcaption><p>Welcome Pop-up</p></figcaption></figure>



**Follow the next steps in following order to setup your first custom chatbot :**&#x20;

1. **Adding Knowledge (RAG)**
2. **Configure LLM**
3. **Create your custom Chatbot in just 5 steps !!!**



#### ✅ **Post-Installation Checklist:**

* [ ] Plugin activated successfully
* [ ] AI BotKit menu appears in WordPress sidebar
* [ ] No error messages in WordPress admin
