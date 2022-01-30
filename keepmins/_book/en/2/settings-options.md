# Settings and options

## Theme options

Admin panel -> Appearance -> Themes Options

In this page, you have 16 options to fill up or choose, fill them up as much as you can then you will have a much better experience using this theme.

### Functionality Options

1. **Posting Access:** Choose if you let any member including none-admin to post on your site.
2. **Hide Threads:** Choose if you want to hide comments threads in default.
3. **Bing API key:** Paste your Bing Map API key to the field, see [chapter 2.1.3](https://doc.dukeyin.com/keepmins/en/preinstall/) on how to get one.
4. **Tencent Map API key:** Olny Chinese users need to fill this up, leave it blank if you are not in China.
5. **Max Image width:** Number 1 to 2000. Image width larger than this will be resized to this number in pixel before upload. Height will be calculated automatically. 612 is recommended. **If you set this number to 1, images will be upload in full size.** Note that your php might refuse to upload if you set this number too large.
6. **Image Resize Quality:** Number 0.0 to 1.0. Image quality for pre-uploading resizeing, set to 1.0 for best quality and largest file size, 0.0 for worst quality and smallest file size, 0.7 is recommended.

### Design Options

1. **Post prompt:** Will appear in your input box when nothing has entered, as a prompt.
2. **Blog Post Titles:** Whether to show “blog” type post title in your post list.
3. **Statistis page subtitle:** You can customize your analytic page subtitle on this field.

### SEO options

1. **SEO Keywords:** Keywords of your website, separated by commas, no more than 32 characters recommended for search engine optimization.
2. **SEO Description:** Descriptions for this site, less than 320 characters, fill this for better seo.
3. **SEO Author:** The author name for this site, fill this for better seo.
4. **Additional codes in footer:** These codes will be insert to page footer, right before body tage ends, use this to add your tracking, analytics codes or any codes you want for whole site.

### Additional options

1. **Date of site found:** Choose the day that this site was open to visitor, theme will use this to get how long the time this site lasts.
2. **Site record No.:** Chinese users need to fill this for a legal reason, will appear in footer info.

Click “**Update Options**” button when you finish them all.



## Personal Options

These options are judged by accounts, when you have multi users, they can set these options differently according to there preference.

WordPress Admin panel -> Users-> Your profile

Scroll to bottom find: “**Extra Options**“

**Gender：**Choose your gender, will be shown on author page

**Detect your device information:** Whether to detect your device info when you login, you can choose not to, detect but don’t show, detect and show.

**Float button position:** The Float button position when you login, choose left or right which best fit your preference.



## Plugin settings



### Post Views settings



Admin panel -> Settings-> PostViews



**View Templat:**



```
%VIEW_COUNT_ROUNDED%
```



**Most Viewed Template：**



```
<li><a href="%POST_URL%" title="%POST_TITLE%">%POST_TITLE%</a> - %VIEW_COUNT_ROUNDED% views</li>
```



Adjustments and settings completed.