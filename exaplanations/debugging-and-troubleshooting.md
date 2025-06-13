# Debugging & Troubleshooting



## Installation Errors&#x20;

### 🔧 Troubleshooting Common Installation Issues

Don't panic if something goes wrong! Here are solutions to common problems. 🛠️

#### 😱 **"Plugin could not be activated"**

**Possible Causes & Solutions:**

**🔴 PHP Version Too Old**

* _Problem:_ Your server runs PHP below 7.4
* _Solution:_ Contact hosting provider to upgrade PHP
* _Check:_ WordPress admin → Tools → Site Health

**🔴 WordPress Version Too Old**

* _Problem:_ WordPress below 5.8
* _Solution:_ Update WordPress via Dashboard → Updates
* _Warning:_ Backup your site before major WordPress updates!

**🔴 File Permissions Issues**

* _Problem:_ Incorrect file permissions (manual installation)
* _Solution:_ Set folders to 755, files to 644
* _Help:_ Contact hosting provider for permission assistance

#### 😵 **"Plugin not appearing in admin menu"**

**Quick Fixes:**

1. **Hard refresh** your browser (Ctrl+F5 or Cmd+Shift+R)
2. **Clear caching** plugins if you use any
3. **Deactivate and reactivate** the plugin
4. **Check user permissions** - you need administrator access

#### 🌐 **"SSL Certificate Required" Error**

**Solutions:**

1. **Get free SSL** from your hosting provider
2. **Enable HTTPS** in WordPress settings
3. **Force HTTPS** using plugins like "Really Simple SSL"
4. **Contact support** if you can't enable SSL

#### 💾 **"Database Error" During Installation**

**Steps to Fix:**

1. **Check MySQL version** with hosting provider
2. **Verify database permissions** - WordPress user needs CREATE TABLE rights
3. **Ensure sufficient disk space** for database growth
4. **Contact hosting support** for database issues

#### 🔄 **"Installation Incomplete" or Stuck**

**Troubleshooting:**

1. **Increase PHP memory limit** (ask hosting provider)
2. **Check for plugin conflicts** - deactivate other plugins temporarily
3. **Clear browser cache** and try again
4. **Use alternative installation method** (switch between Method 1 and 2)

***

### 🆘 Getting Help

If you're still having trouble, don't worry! Help is available. 🤝

#### **📞 Support Channels:**

1. **Plugin Documentation** - Check our other guides
2. **WordPress Forums** - Community support
3. **Hosting Provider** - For server-related issues
4. **AI BotKit Support** - For plugin-specific problems

#### **📊 Information to Provide When Seeking Help:**

* WordPress version
* PHP version
* Plugin version
* Error messages (exact text)
* Steps you've already tried
* Hosting provider name

#### **🔍 Debug Information:**

Enable WordPress debug mode to get detailed error information:

1. Edit your `wp-config.php` file
2. Add: `define('WP_DEBUG', true);`
3. Check error logs for specific issues
