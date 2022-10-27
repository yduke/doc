# Pre-install

## WordPress

- A fully functional WordPress site with admin privileges
- SSL certificate encryption. ( https protocol access )
- **All WordPress required and recommended PHP modules are installed (check on WordPress admin panel – Tools - Site Heath )**
- You can customize site themes
- You can customize site plugins
- Better if you have FTP access to your “wp-content” folder
- You can upload attachments
- You can modify the permalink format

Recommended: WordPress permalink set to：

```
/%post_id%
```

So each of your posts link will be like：

```
https://yoursite.com/1234
```

You can change permalink format at： WP admin panel -> Settings -> permalinks -> Custom Structure

Long and complicated permalink formats are not recommended.

## Files

When you receive this theme, 2 files are included：

- keep-minutes-2.zip
- wp-postviews.zip

These 2 files are all we need for setting up the theme, put them to location where you can found and prepare to install.

## Theme license key

The license key code for the theme is attached to the email. The license key code is unique and can only be used by you.

The number of theme that the activation code can activate is limited.

Remember, don’t expose the activation code to others. If someone else used the activation code, you won’t be able to activate your theme.

## Get a Map Service API Key (Optional)

*This step is optional, but if you skip this step, the geo location function will not work.*

The “Check-in” function of theme relies on Map service, choose Bing map service API key if your site language is English, and you are in US/Canada/German/Italy or Spain.

Choose Tencent map API key if your site language is Chinese and you are in China.

The 2 map service will switch automatically depending on your Site language setting, so you only have to choose one to fit your main language.

For example: My site language is English and I lived in US, I only have to get a Bing map API key.

### 4.1 Bing Map API Key ( for English users )

#### Step by step：

1. Go to https://www.bingmapsportal.com/

2. Click on “Sign in” and sign in with your microsoft account.

   If you see

   ```
   Do you want to use the account xxxxx for your new Bing Maps account?
   ```

   Click “Yes” and fill up the next form to create your Bing map account.

3. Move to “My account” on top left and click “My key”.

4. If you have no keys in your account, it will lead you to “Create key” form, fill the “Application name” and choose “Basic” for your key type, “Website”for Application type.

5. Then click “Create”.

6. Click the blue part “Show key” and copy your key below.

7. Put your key to somewhere safe and wait to be serve.

 

### Tencent Map API Key ( for Chinese users only )

#### Step by step：

1. Go to [https://lbs.qq.com](https://lbs.qq.com/)
2. Click on the menu on the top right corner of the homepage:”**控制台**“, login with your QQ or Wechat account.
3. Click on the left after successful login: “**应用管理 - 我的应用**“
4. Click “**创建应用**” then input the name and category you like.
4. After that, click "**+ 添加Key**" on top right of page.
5. Name your key at “**Key名称**“, any word you like, description it in “**描述**”, like “my check-in key”, After completing the verification code, click “继续” to continue.
6. In”启用产品”, make sure  “**Webservice**” are checked.
7. On “**域名白名单**” field and enter the domain name of the website, if your website is https://www.twitter.com , then your white list should be:

```
 twitter.com
```

Click”保存” to save, and copy your key to somewhere safe wait to be serve.

 

There are limits in both service key for free user, so use your own key and do not share with others is a good idea.

If you over use the geo-location function in theme, additional charge from map service may apply.

## 10 minutes time

Installing theme is easy when you get all stuffs you need, now you need 10 minutes free to move on to the next chapter.