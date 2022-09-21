# Change log

## Keep Minutes  2.9.9.8.18

September 19, 2022

- Adjusted the position of the like counts
- Before click heart, visitors need to enter temporary identity information to record the their identities



## Keep Minutes  2.9.9.8.16

September 07, 2022

- Support direct posting of URLs of Bilibili, NetEase Cloud Music, YouTube, Spotify, Vimeo for inserting media
- Fixed the style of dialogue articles
- Buttons add rounded corners
- Adjusted the color of some buttons



## Keep Minutes  2.9.9.8.15

September 05, 2022

- Add button to clear temporary visitor identity
- Aside posts can now be fold, style updated
- Asid posts avatars on community pages linked to site home pages



## Keep Minutes  2.9.9.8.14

September 04, 2022

- Rearranged post creating form in home page for a little bit.
- Rearranged actions buttons for a little bit.
- Fixed an issue that may cause the text expand failure.
- Formatted some htmls of icons.
- Aside post contents can now be hidden or expand by click.
- Like from aside post.
- Visitors can now set their identity temporarily with cookie for their likes and comments.
- Add blacklist option for community.
- Register page url now detected by program, so no need for option.
- Add aside post action name data for km post json api.



## Keep Minutes 2.9.9.8.10

August 28, 2022

- Load "image uploading" JavaScripts from a file instead of embedded it in page
- Community "likes" will open into a new window to avoid being blocked due to cross-site policy
- Improve the external-like, heart mechanism



## Keep Minutes 2.9.9.8.9

August 27, 2022

- Remade the layout of the composing interface buttons and enlarged the size of each action buttons
- The Cancel button is added to the aside post compose interface, and the default state of the writing interface is restored when it is closed or canceled.
- Adjust the position of emoji button, check-in button, weather indicator icon
- Adjusted the text size of the location address and device name in the compose interface
- Prevent from loading dash-icon icon style in frontend
- Adjusted the hover background color of each options in the voting interface
- Optimized the navigation buttons after page breaks in articles and pages
- Infinite Scroll is no longer performed on pages that do not require Infinite scroll
- Fixed new video and sound files not showing up after infinite scroll
- Added a unicode option to the "emoji CDN" options  use the built-in emoji on the client device system
- Created a new API to accept heart requests from outside
- Prevent same likers information from appearing repeatedly
- Adjusted the UI size and layout of the forced login interface
- After login failed in each login interface, it no longer jumps to the original WordPress login interface, but sends a notification
- Made the OK button of the pop-up layer translatable
- Replace old deprecated formats in script files with current formats
- Password input boxes on all login and registration interfaces are disabled from auto-completion.
- Prompt the user to close the top Adminbar after login
- Optimized the quote posts style in community page
- Optimized RTL style



## Keep Minutes  2.9.9.8.4

August 24, 2022

- Update infinite scroll scripts to latest;
- Search result and archive pages are now infinite scroll-able; 
- Add a lot of icons to aside post with groups;
- Statistic page now show the total action for aside post for each users;
- Pop  up lightbox for creating polls and lists.



## Keep Minutes  2.9.9.7.3

August 03, 2022

- Add a like button to the community page;
- Add the title detection of repost articles;
- Added force login to view function;
- Added buttons for common text formatting;



## Keep Minutes  2.9.9.7.2

June 19, 2022

- Fixed resource path errors, compressed JavaScript files;
- Album pictures are in medium size to reduce picture traffic;
- Added long graph indicator;
- Shortened the page load timeout threshold;



## Keep Minutes  2.9.9.7

June 7, 2022

- Fixed album style disappear after infinite scroll;
- Fixed rounded corner styles for albums and pictures;
- Corrected the address of the header cover images;
- Adapt to responsive images, and the album automatically selects a lower resolution after upload;



## Keep Minutes  2.9.9.6

May 30, 2022

- Vertical video downsizing;
- Adapted to the new version of WordPress, and corrected the album style.



## Keep Minutes  2.9.9.5

May 18, 2022

- Add progress bar <progress> style;
- Optimized editor style;
- Disabled widget block editor;
- Added theme option to choose appropriate emoji CDN source



## Keep Minutes  2.9.9.2

April 07, 2022

- Fixed an issue that images in gallery might zoom out when click;
- Remove unnecessary styles in theme.



## Keep Minutes  2.9.9.1

March 02, 2022

- Adapt new WordPress code and pre block style，and now you can copy contents in code and pre;
- Remove old icon files and styles.



## Keep Minutes  2.9.9

March 01, 2022

- Change to the new WordPress album code format, compatible with the old album format;
- Post contents no longer automatically adds p tags;
- jquery and some JavaScript CDN changed to cdn.staticfile.org;
- The read more button goes to center.



## Keep Minutes  2.9.8.6

February 08, 2022

- Removed a lot of description text in the tag group page
- Aside post (little status) will not contain image(s) any more
- Fixed spelling mistakes in ReadMe.txt
- Optimized the logic of obtaining device information



## Keep Minutes  2.9.8.5.2 

January 27, 2022

- Fixed some bugs caused by Minify;
- Fixed Ajax misbehavior for editing comments;
- The default WordPress registration link will now redirect to the built-in registration template page;
- Updated the mobile detection script;
- Fixed incorrect styling of the theme options page on mobile;
- Fixed script errors for voting;
- Numerous corrections to previous spelling mistakes.



## Keep Minutes 2.9.8.5

January 16, 2022

- Redesigned RTL CSS style;
- Added Arabic (Ar) language pack;
- Reorganized the file structure;
- Added “Poll” or Vote feature;
- Lots of bug fixes, removal of lots of deprecated files or code snippets.



## Keep Minutes **2.9.8.4**

December 30, 2021

- New user registration page template;
- manifest.json is changed to PHP processing to adapt to different websites.



## Keep Minutes 2.9.8.3

December 20, 2021

- Removed the height of the table, for adaptive;
- Fixed some styling bugs;
- The picture LightBox click effect script is updated to the latest version;
- Added prompt text to dialog post UI.



## Keep Minutes **2.9.8.2**

December 04, 2021

- .Fixed the bug that clicking the “Repost” button on the single page was invalid.



## Keep Minutes **2.9.8.1**

November 14, 2021

- Add support for .mov video file;
- Make check-in map shortcode even better.



## Keep Minutes **2.9.8**

October 14, 2021

- Fixed the incorrect display of the sign-in static map on the mobile device;
- Fixed the page margins that were too large on mobile devices;
- The REST API detection on the “Join community” page was changed to the correct custom address.



## Keep Minutes **2.9.7.9.9**

October 12, 2021

- Fix the tag link in the community;
- Fixed the error that the community content could not be obtained due to SSL issues;
- Improved the display mode of the tags and the display mode of the containing tags;
- The access point of the weather api has been updated, and the old access point will soon be abandoned;
- Some style improvements.



## Keep Minutes 2.9.7.9.7

September 25, 2021

- As the CDN where the community data is often ventilated, the data has been transferred to the local at present;
- The default REST of WordPress is no longer used, and the community content is output according to the custom REST of the previous version;
- A field of site address has been added to the API;
- The community can now display tags;
- The logs in the community can correctly handle “idle” actions;
- Improved the appearance of “login to comment”.



## Keep Minutes **2.9.7.9.5**

September 23, 2021

- When the local web browser can’t or failed to convert image to webp, the uploaded images will be converted to webp in server-side by GD or imagic;
- A registered user or one who with WordPress comment identity liked your post, their name and avatar will show at the bottom;
- [Community] Custom REST API added for large and fast data capacity;
- [Community] Click comment icon will lead you to the comment box of the single post;
- “Theme color ” of now changed to black;
- Style optimized.



## Keep Minutes **2.9.7.9.4**

September 14, 2021

- Fix image style and a link error in “community” page template;
- Fix an issue on the top image of the user profile page;
- Rewrite the style of post contents;
- A new way to handle the p and br tag in post content;
- Reposted content now have their own tag(s).



## Keep Minutes **2.9.7.9.2**

September 09, 2021

- Add “Community” features, including a “Community” page template.
- Add “Age” option to the users’ profile page.



## Keep Minutes 2.9.7.9

September 04, 2021

- “Repost” feature added;
- “Aside” (Mini Status) feature added;
- Since safari on iOS does not support webp image conversion, a judgment has been added that pictures published on iOS device will remain jpeg, pictures uploaded on other platforms will be converted to webp first;
- Improved some old styles.

### Repost

- Repost will take effects on published posts and pages;
- Repost will be invalid when the original post or page get completely deleted;
- Repost can be nested infinitely.

### Aside (Mini Status)

- Aside will be a separated post format;
- Aside post can be published without post content;
- Aside posts will automatically get description text as you choose, except the “blankface” one was your choice.

![img](..\assets\en.png)





## Keep Minutes 2.9.7.8

Aguest 05 2021

- Fixed an issue where weather data could not be obtained due to the weather API update.



## Keep Minutes 2.9.7.7

Aguest 04 2021

- Prevent visitor comments using amdin username or email;
- Adapted to WordPress 5.8, fixed some block styles in front end.



## Keep Minutes 2.9.7.6

July 22 2021

- Improved the scripts for highlighting specific comments by comment URL;
- PHP to detect IE browser, and no warning text will be output to the html code in non-IE browsers;
- Fixed some bugs in sidebar widgets;
- Pictures and photo albums in small devices are now wider.
- Images uploaded from front-end will be converted to webp automatically, reduces the file size and saves the traffic. (WordPress 5.8 needed)
- translation updated.



## Keep Minutes 2.9.7.5

July 12 2021

- Adapt WordPress native lazyload for the pictures in all page templates;
- Optimize the wp-block-cover element in dark mode;
- Update JavaScripts to further prevent video and audio from being downloaded;
- Added the option to load the main jQuery from an external CDN;
- Header SEO optimization;
- Add left and right sidebars (beta);
- Removed the html title filter, because WordPress is processing it itself;
- Added admin notice for missing dependencies;
- Add cover and caption to the video input box;
- Optimized the style of the input box;
- The suffix of reading numbers is removed, and cofigeration of the Wp-post-views plug-in is no longer required for new installations.



## Keep Minutes 2.9.7.4

June 22 2021

- Gallery style imporved;
- Font-size in mobile deivece is now normal;
- Light-box scripts updated;
- Light-box can now navigate the next and preious images in one post.
- Light-box shows total number of images and the title;
- [Pravicy] No longer save geographic location locally;
- Ajusts the qoute styles;
- Optimize the tags style.



## Keep Minutes 2.9.7.3

June 10 2021

- Add fade out effects when scrolling;
- Compressed the main JavaScript files;
- Bugs has been fixed.



## Keep Minutes 2.9.7.2

June 06 2021

- Slightly enlarged the width of the content area
- Videos are now full width on the phone
- 3 new Chinese Gravatar CDN added.



## Keep Minutes 2.9.7.1

May 27, 2021

- Optimized images styles on small devices
- Add a function to get image from post
- Styles for video subtitles
- Preventing videos from downloading by visitors
- Preparing support for PHP8, fixed a lot of issues.
- Optimized the process of activation and authentication.



## Keep Minutes 2.9.7

February 18, 2021

- The tag thumbail in Tag Group was stretched, this is fixed now.
- Improved notification for local browser.
- Theme support widget in dashboard was improved, download and documents link was added, also there will be a copyright statement.



## Keep Minutes 2.9.6.8

December 09, 2020

- Fixed the light-box effects for gallery posts on new WordPress.



## Keep Minutes 2.9.6.6

December 03, 2020

- Fixed the wrong styles in search results for dialog posts.
- Fixed a bug that the image thumbnail did not have rounded corners at the bottom.
- The web notification will no longer have an html hard link code.
- Comments styles optimized.



## Keep Minutes 2.9.6.5

October 08, 2020

- Fixed an issue that cause the admin menu can not unfold, this issue was caused by user profile background image uploading scripts previously added.
- API updated, fix an issue that gives “undefined” tag when use API.
- Add “Popular tags” (Trending) and “most recent tags” (New things) to tag groups page template.



## Keep Minutes 2.9.6.4

October 07, 2020

- Solve the performance problems caused by session of tag groups;
- Tag group page template style optimization;
- The create button under the single tag page can now be displayed normally;
- Fixed the problem that all pages will load the media library script;
- Optimized the style of the author page on the mobile screen；
- Add an option to choose whether to load style and scripts from CDN;
- Descriptions and instructions on theme option page optimized.



## Keep Minutes 2.9.6.3

September 21, 2020

- Ability to customize the logo in Appearance – > Customize -> Site Identity.



## Keep Minutes 2.9.6.2

September 14, 2020

### Tag functions upgrade

- Featured image for tag, and show the image on tag page.
- Tag group: Create tag groups，assign one or more tags to one group;
- New tag group page template to show grouped tags;
- Add a button to tag page, click this button will help you create post for this tag;
- New theme options to switch tag group function on or off;
- New button to clear tag group data and shut this down.

### Other updates

- The logout button has moved to very top of page, gives more space for control buttons;
- Rewrite styles of the site description.
- Added a new homepage URL parameters API, now we can use URL parameters to fill-in the title, content and tags of the article;
- Part of dark mode style optimizations.



## Keep Minutes 2.9.5.6

August 26, 2020

- Update the version of jQuery.scrollTo to 2.1.2;
- Fixed the length of the “top search button” and” upload video button” in the English version due to the different character problem;
- HTML5 support for styles and scripts has been added according to the latest WordPress standards;
- Solved the problem that when there is a sticky post, the count of uploaded images will always be calculated based on the ID of the sticky post, this cause images cannot be uploaded after the limit is exceeded;
- Main JavaScripts are optimized based on the new jQuery that built-in WordPress 5.5.



## Keep Minutes 2.9.5.4

August 12, 2020

- Geting commentor’s user agent to show system and browser info down to their comments.



## Keep Minutes 2.9.5.3

August 12, 2020

- fix an issue that cause page not load properly on new WordPress 5.5.



## Keep Minutes 2.9.5.1

July 22, 2020

- Add a author page background image, this can be set on your edit profile page.
- “Last update date” on “Keep Minutes theme support” widget can now show local date correctly.
- Corrected some old expressions and grammars in accordance with the latest WordPress theme standards.



## Keep Minutes 2.9.5

July 20, 2020

- Image templates can now display external images correctly.
- Improved the styles of pre, code, table and blockquote.
- Simplify the animation of expanding and collapsing long texts.



## Keep Minutes 2.9.4.9

June 10, 2020

- Fix an bug that /n cannot be converted to <br>.
- Now you can choose wheather to upload your video to media library or paste a video URL.



## Keep Minutes 2.9.4.8

June 01, 2020

Optimize the license verification process

- When the verification server returns an error or blank message, the theme will ignore it and the activation status will not change.
- When the verification server is offline or in an unresponsive state, the activation state will not change.
- Only the following 2 situations will automatically deactivate the theme:
  - The verificaiton server returned “Blocked” or “Unauthorized”;
  - No local domain name was found in the verification server.
- For the inactive front-end, the red prompt no longer appears, and the prompt is changed to the back end.



## Keep Minutes 2.9.4.7

May 30, 2020

- Add a ring as a word count indicator, from the user-set maximum number of words to 0, to form a closed loop.
- Added video embedding function, temporarily accept only external video link, format mp4 ogg or webm. You need a fast video source server.
- When the post is published, all temporary input boxes are hidden and the word count is reset to zero.
- Optimized the experience when deleting articles or comments failed.
- Added an easter egg, can you find it?



## Keep Minutes 2.9.4.6

May 22, 2020

- Dialogue mode! Want to experience the highest level of loneliness?
- Updated the style of the author page and added some data.
- Prepare for video posts.



## Keep Minutes 2.9.4.5

May 10, 2020

- If your post is too long, we can now collapse it to a short one by default, one click to expand.
- You can now set the character indicator number to any number you like other than 280.
- Fixed a bug where the title could not correctly intercept the content.
- Translation update.



## Keep Minutes 2.9.4.3

May 06, 2020

- Optimize for Child theme.
- License verification optimized to reduce false deactivation.
- Attachment template optimized.

Download Child theme： [Click here](https://www.dukeyin.com/download/keep-minutes-2-child.zip)





## Keep Minutes 2.9.4.2

May 05, 2020

- Fixing bugs sthat uploading photos taken from phone or camera can not rotated correctly;



## Keep Minutes 2.9.4.1

May 01, 2020

- Fixed a bug that uploading photos taken from phone or camera can not rotated correctly;
- Admin page dashboard widgets had new inflammations on it .



## Keep Minutes 2.9.4

April 21, 2020

- Fixed some adaptive styles on small screens like iPhone 5 and iPhone SE;
- Fine-tuned the color scheme of the dark mode;
- Some elements are changed from ID to Class, the code is more neat;
- Fixed bugs that pictures and galleries are displayed incorrectly under the new version of WordPress 5.4;
- The two plug-ins originally needed: Infinite Scroll and jQuery smooth scroll have been integrated into the theme, these two plug-ins do not need to be installed anymore;
- Template Image-gallery, Image-inline and template geo-location list are now infinite scroll enabled.
- Add custom loading and loading completion text on the theme options page, also a infinite scroll switch for whole side;
- The image-gallery template is now unified with the new album code.
- A theme version indicator is added to the WordPress admin page dashboard to make it easy for users to know what is the latest version.
- Now with an updating server, you don’t need to get zip file from email, just click update, theme will be updated.



## Keep Minutes 2.9.3

March 09, 2020

- You can now get weather information while you’re getting your location;
- 43 new weather condition icons added, will show on left top of your post if you choose to share weather information, temperatures and condition name will be in title of the weather icon;
- Geo location template now has weather icons too;
- Set your weather API key on theme options page, set to show or hide weather info on your profile page;
- Theme options page has been reorganized；
- Some of the icons modified to look better, some unused files had been removed.
- Improved the text of the “More” tag link.
- Improved the search result page “key words highlight” functions for non-English language.
- Tag description added to the tag archive page, edit each tag in admin page to show it’s descriptions on front-end #tag page.



## Keep Minutes 2.9.2.8

March 06, 2020

- Fixed a bug that a sticky post will always show on ” locations template”.
- Add an option “hide” to the float button, change it on your profile page.
- Random template can always find a post to show now.
- The frequency this theme verifies it’s copyrights with remote server has been reduced.
- Improved iframe style so your YouTube embed videos will be just fine.



## Keep Minutes 2.9.2.7

October 07, 2019

### Text Input

- The input content (post content, comments) will be stored in the local browser in real time, when the browser is mistakenly closed, or jump to another page, the previously entered draft content still exists till you publish it.
- The prompt “There is unsaved draft content” when jumping to other page is canceled.
- Enter “#” in the content body to automatically identify it as a tag, and save it as a tag when publishing, similar to Twitter.
- When there is “#” in the body, it will remain its position with link in the body, and the tag list at the end is not shown repeatedly.

### Image Uploading

- Images upload by Non-admin users will save in separate directories named by their username.
- Non-admin users can only see the media files upload by themselves in the media library.
- Image file name is now “date upload” and 2 random characters.

### Copyright Protection

- Now you need a licence key to activate theme, other wise theme will not run normally.
- Activation process will communicate with remote serve and verify if the code is valid or invalid. This process will run at regular intervals.

### Other

- In the article, when the width of a single image exceeds 315 pixels, it will be reduced to 315 pixels, click to enlarge, and then click to zoom out.
- “Geo location list” template now with check-in date under each check-in post.



## Keep Minutes 2.9.2.6

September 27, 2019

- Now This theme can detect your device info like device name, os name and save theme in your post meta，new posts will have “From iPhone iOS Safari” or “From Samsung Android-OS Chrome” etc on bottom. Mobile and tablets only.
- You can set whether to detect and/or show your device info in your profile setting page.
- Improved the way tag input, after input some text, press enter or comma will create a tag block, click on existing tag to delete one tag.
- Add the Gravatar CDN option to choose the fastest CDN for your needs.
- The floating button position option is changed from the theme option to the profile page. When multiple people use this theme, they can choose floating button to be left or right differently depending on their needs.
- Text paragraph and line break style corrections.
- “Send it” button now have a new look: an icon of plan.
- New images page template, use native WordPress gallery scripts, more reliable.



## Keep Minutes 2.9.2.5

September 18, 2019

### English Version！

1. English version UI optimize, killing bugs；
2. Integrate Bing Map API，switch map engine according to the site language, use Tencent map when selecting Chinese, and Bing Map for others;
3. Bing Map API Key customize input field in theme option panel;
4. Bing Map API chick-in: get your adress POI and static map png;
5. Interactive words in English optimization.

![img](..\assets\english-geolocation.png)

Bing Map Geo-location in English



![img](..\assets\chinese-geolocation.png)

Tencent map Geo-location in Chinses



Currently Bing Map’s location identification API supports Canada, Germany, Italy, Spain and USA. Check-in will be available in these country with English site language. Microsoft will add more country or region in the future.



In addition to China, the location indentification and check-in function in Keep Minutes theme is now support six countries in all.





## Keep Minutes 2.9.2.4

September 11, 2019

1. When switching pages, there is now a fade in/out effect.
2. The effect of fading the top and bottom on a single page was removed.。
3. Open Graph protocol meta has been added to the header.
4. The @”user name” has been added to the display name.
5. The action buttons of the main interface is now more flexible, more fit for small screen device.
6. Adapting old device like iPhoneSE iPhone5.
7. A new avatar, name, username, profile, and URL is now added to the author page.
8. The “Gender” option is added to the profile content, and if it is set, it will be displayed on the author page.
9. A new masonry image display template has been added, and there are now three ways to display images.
10. Discard the old spin.js and replace the background indicator with the animation svg.
11. Emoji’s cdn was replaced by cloudflare, which seems to be faster than before.
12. The “Stick post” has a special style now, and the newly published articles and comments have a specific style too.
13. When the new post form other place is received from local, the new post will appear from the top and turn yellow (the dark mode turn brighter), and the original color will be restored when the page scrolls.
14. Jquery.jeditable.js has been updated to the latest version.
15. Toggle all comments now with smooth animations.
16. Mobile comment boxes style optimization.
17. Fixed a bug where the image template was sorted out wrongly in MacOS Safari.
18. “Logout” button adds a pop-up confirmation.
19. All Textarea can be increased or decreased depending on the content (previously only increased). Includes: main input box, comment box, and edit content box.
20. A single post adds a rounded corner effect.
21. Archive template optimized, when viewing categories or annual months it will be normal.
22. Some translations have been improved. Some styles of the English version have been improved.



![img](..\assets\Capture2.png)

New post auto load



![img](..\assets\Capture.png)

New post on dark mode



### “Link” post format improved：

1. Add an input field for entering a URL in front post box;
2. When url input field lost focus, this url is automatically parsed, Keep Minutes will get its tilte, description etc.
3. Keep minutes will automatically typeset and fill these info into the main input box, waiting for editing and publishing.



I was thinking the “link” post was useless and wanted to remove it, now the link post was renewed.





### Spring cleaning: streamlined theme files

1. Removed the Baidu sharing function, the huge statics folder was deleted, and redesigned the “sharing” function.
2. Style.css is too old and has accumulated a lot of unnecessary styles. To solve this, a lot has been done of cleanup and optimization, reducing the original 1300+ lines to 800+ lines, discarding all the styles of sidebar styles and discarded elements. Optimized all input element styles.
3. Combined the “heart” “Floating button” and “Statistic page number” js file to one, reduced the file size.



Theme pack file size reduced from 800+kb to 500+kb.



### Dark mode enhancement:

1. The color scheme details of the dark mode have been adjusted and the overall color is darker.
2. The dark mode floating controller is unified in red.
3. When a post or comment posted on another device is obtained, the new content can also be highlighted in the dark mode;
4. Fixed some input boxes dark styles;
5. Fixed the color of the top expanded menu button.



## Keep Minutes 2.9.2.3

September 1, 2019

- Fixed: The upload function is still valid when uploading images for the 2+th time.
- Fix: When there is content in the input box, the new uploaded image code will be added after the old content (previously replaced)
- New: Theme option can now set the maximum uploading picture size (set to 2-2000), or full size upload (set to 1)
- New: Theme option can now set the quality of uploading picture after resize the picture, 0.1-1.0.
- When a new content is posted or a notification is received, there will be a sound effect, only when on desktop device.
- New：Emoji selector in main post box.
- Gravatar CDN change to v2ex, which is faster on updating new gravatar.

WordPress’s emoji display relies on s.w.org (WordPress’s own server) so it will be slow to visit in some place, looking for emoji’s CDN to speed up the display of emojis.



![img](..\assets\emoji.png)



## Keep Minutes 2.9.2.2

August 18, 2019

- Add a trash can icon to delete a post from front end.
- Add the Ajax function to support delete post and comment from front end.
- Actions button style adjustments.
- Add functions when there is no ajax the delete functions still works.
- Error messages are now shown on spacial field in red, localized all error message.
- 

## Keep Minutes 2.9.2.1

August 14, 2019

- Add a shortcut “S” and press it on all non-single pages to display the search box.
- Add a shortcut key “Ctrl+Enter” to submit and publish contents or comment.
- The ajax delete post now worked in progress, not work well, needs improve.
- All the images in “dark mode” changed from the original reduced transparency to the filter brightness, so it will be normal when multiple images overlap.



## Keep Minutes 2.9.2

August 13, 2019

- Thanks to the NPU @haimenese for helping me solve the problem of uploading multiple images at the same time, the latter pictures will repeat multiple bugs.
- ToDo：Start adding a feature: delete a post or comment in the front-end with Ajax.



## Keep Minutes 2.9.1

July 25, 2019

- The original old label is replaced with HTML5 tags, basically conforms to the HTML5 specification, IEs goodbye.
- Hidden word limit when switching to “blog” fromat.
- Check-in list style improved.



## Keep Minutes 2.9.0.3

July 25, 2019

- Switching post format animation is smoother than ever before.
- The animation of the new post is published, and the animation of the new commentis published is smoother.
- Shortcut help tips and notify window tips are smoother, and the location is normal on both the desktop and the mobile device.
- Search module now move to top, and slide down when you call for it.
- When you post something in other place, new post will slide down form top, as well as the comments.



## Keep Minutes 2.9.0.2

July 16, 2019

- Keyboard shortcut repaired. Now you can use the keyboard shortcuts normally.
- Attachment page style correction.
- Multiple permission logic corrections.



## Keep Minutes 2.9.0.1

July 15, 2019

- New upload component is fully functional
- When uploading a picture, the output is a WordPress image block, and when it is more than one picture, album block is output.
- There is still a problem that photos cannot be rotated according to the exif information.
- The photos taken by the mobile phone can be rotated correctly (thanks to NPU @haimenese). Pictures will be resized before uploading by native browser. The default resize width is 800px, the height will be calculated automatic, and the resize-to width number can be manually adjusted in theme options.

![img](..\assets\gallery-upload.png)



## Keep Minutes 2.9.0

July 10, 2019

Impage uploading:

- Discard the original embedded media library
- Change to Ajax upload, then attach images to the media library on the server, randomize the file name
- Currently only one image can be uploaded at a time, and the album and multi-image need to be edited in the background. Working on it.
- Plan: Using html canvas to resize the large images before uploading.



Extra:

- Added floating button to check in, upload image(s), and write anywhere on the homepage
- Responsive style correction for desktop themes
- Improved the check-in function and map displaying, add a “insert map” button.
- When visits number is greater than 10000 in statistic page, it will automatically change to *K in unit.
- 5G is coming, next step is to cancel separated mobile theme, one theme to rule them all!



- ![img](..\assets\float-button.png)
- ![img](..\assets\statistics.png)
- ![img](..\assets\locations-dark.png)



## Keep Minutes 2.8.0

June 23, 2019

- No longer rely on p2 theme, published as a independent theme
- Page width is expanded to 860px
- Statistics page template rewrite
- The theme options panel is merged into one by the original two panels.
- Change all avatars to gravatar, no need to upload images, please test the speed yourself.
- Multiple css and js corrections
- Rewrote the style of the album image.
- Built-in Lightbox effect, now you can have a lightbox effect without installing a plugin
- Sharing function is built in, no need to add static directory separately
- Remove Baidu statistics options field, now you can use any other statistical code in theme options panel.
- Dark mode

![img](..\assets\dark-mode.png)



## Keep Minutes 2.7.3

March 15, 2019

- Fixed a bug that two same post will be published occasionally.
- Fixed a bug where the title of the “Blog” post would NOT be displayed on the desktop theme.
- Nothing else.



## Keep Minutes 2.7.2

March 13, 2019

- Fixed an issue where desktop theme commenting was disabled in WordPress 5.1.1.
- Fixed an issue where the “Blog” content was posted and the title was not displayed. The current “blog” type of post (standard) will display the title on both the phone and the desktop.
- Fixed a bug where the page of mobile theme would not display the title.
- Fixed a bug where some templates and pages on the phone theme didn’t show the post date and time.
- A “full-editor” template has been added to the desktop theme, so you don’t have to switch to the mobile theme when setting up your mobile phone full edit template.
- Fixed a bug that a warning in the front end of each post in the PHP 7.3 environment.
- Below PHP 7 will no longer be supported.
- Correction of some details.



## Keep Minutes 2.7

August 14, 2018

- Get rid of the “WPjam Basic” plugin completely, now you don’t need to install this plugin, you don’t need to register ANY account. Grab the theme and use directly. Users can choose whether to connect a CDN or not, it up to you.
- Built-in new php image resize plug-in, relying on WordPress internal mechanism to process images, safe and stable, does not rely on any third parties.
- Fixed multiple code errors and WordPress standards errors.
- A full English version and the corresponding Chinese language pack were created, and theme language changes with the WordPress back-end language settings.
- The phone theme has a new single-page, comment, and like button.
- The word limit has been expanded from 140 to 280 words.
- Correction of some details.



## Keep Minutes 2.6

May 11, 2018

![img](..\assets\keepmins2dot6screenshot.png)



### A new options control panel has been added to the background to customize the details:

- The “Tencent Map API Key” required for location identifying and checking-in can now be filled in by yourself in the panel.
- The keywords, descriptions, and authors of the SEO section can now be filled by yourself for your own site, which is more conducive to SEO.
- No need to replace the avatar, you can now fill in an image URL in the control panel, the whole site (including the mobile version) to get an avatar, it is more convenient to change the avatar. (Gravatar is slow, stick to it.)
- Only need your number to make your Baidu statistic work, if you don’t need it, leave it to blank, and theme will not load any baidu scripts.
- There is an “Online time” in statistic page, now you can fill the date your site was found and the calculation is more accurate.
- The record number can be filled in directly in the panel and shown at the whole site.
- All custom information only need to be filled in once, and both desktop and mobile can use theme to improve your experience.



### New Templates

- Add a “Location List” template, create a new page in the background, select the geo-list template, save the release, you can list all the geographical locations.
- Add a “Site Map” template, create a new page in the background, select a sitemap template, better for seo.
- Improved the “images list” template, images template, effects like this.



### Detail correction

- The search function on the desktop homepage is available.
- The shadow of each post ‘card’ changes more naturally.
- Fixing the views number of the statistics page does not animat bug.
- The old version of css for desktop and mobile versions has been removed, and the new style.css has been streamlined. All statements are as refined as possible, reducing file size.
- The various files in the theme streamline the code, remove extra line breaks and spaces, and reduce the file size.
- Fixed some buggy links and mappings.
- All dead links are removed, replaced with functions, adapted to each individual website.
- The desktop version avatar on the left side of the text, which is currently linked to the theme options settings.
- The mobile version of the first post font is slightly enlarged, the page color is slightly adjusted.
- Updated the thumbnail of the theme, shown in the theme list in back-end.



## Keep Minutes 2.3

October 23, 2014

- Discard the category select plugin, because it make things not clean.
- Adjusted most of the page styles, adjusted a lot of colors
- I decided to create a location-based check-in function similar to Foursquare. After testing, I chosed Tencent Maps. Most of the functions were implemented but there were bugs. works need to be done.
- The avatar is styled and now in round shape.
- The number of words counted has become larger and more conspicuous. When the number of words is about to reach the limit, it will be displayed in orange and red.
- Rewrote the mobile theme, basically the same as the desktop theme, and does not rely on any third-party plug-ins.



## Keep Minutes 2.0

September 23, 2014

![img](..\assets\km2_screenshot.jpg)

- Redesign interface, card design, vector icon
- Responsive design optimization, no need to move themes, perfect for most all desktop and mobile devices, optimized for mobile devices
- “1.0 Series” stops updating



## Keep Minutes 1.3

July 17, 2014

- All icons on the website are replaced by the original gif bitmap as a vector font icon, and well for the the Retina screens;
- Creating icons for single-page post reading, commenting, editing three functions and adapting to screen size to hide/show labels;
- The category select drop-down option has been added to the post interface, and now you can directly select the article category;
- Solved the problem of the previous version “Cannot edit and update Weibo directly in the foreground”;
- Improved navigation menu colors and styles;
- The logout button in desktop version is now moved to the top right corner of the post box;
- Add transition animation for most elements;
- The comment filed of the single page is changed to off by default, and the comment button clicked, field is shown.
- The theme name was officially changed to the “Keep Minutes” directory structure change;
- Official website domain changed from t.dukeyin.com to www.keepmins.com, in an Alibaba cloud server, increased the load speed.



## Keep the Minutes 1.2

July 3, 2014

- Add a “random” page template, you can randomly display a post in all now.
- Built-in Google font Open Sans also used for front-end calls, without accessing Googlefonts, greatly speeds up page loading.
- OpenSans in front end, more beautiful.
- Responsive Design, adaptive small screen device, the text size is unchanged on the small screen non-mobile phone theme, the frame is adapted, the avatar is reduced, and many other elements are optimized;
- Vector fonts is used for Logos, retina screens such as iPhone iPad are never distorted;
- Add a “menu” to the mobile theme to customize the mobile menu items in the WP background;
- The “random” feature in the mobile theme is optimized to fit the mobile theme.



## Keep the Minutes 1.1

May 24, 2014

- iOS7 flat design mobile phone theme, more concise and more beautiful;
- By default, the mobile phone does not load the microblog image, which improves the loading speed of the mobile phone and reduces the traffic;
- The “Logout” button has been added to the mobile phone theme, and now you can log in and log out freely in your mobile phone.
- Mobile phones and desktop themes are added to the “X minutes ago”, “X days ago” and other human readable time. The posts that do not exceed one week are displayed as human readable time, and the posts for more than one week are displayed as normal time;
- In the desktop theme, adds Baidu sharing, which allows readers to share with major social networks;
- Many bug fixes and styles are improved.



## Keep the Minutes 1.0

May 26, 2013

![img](..\assets\ktm_1.jpg)

- Redesigned the interface, abandoned the sidebar, and continued the basic gray and blue color of Beta;
- Developed as a child theme of WordPress free theme P2;
- Accurate 140-word limit real-time judgment;
- Discard some of P2’s post formats, leaving only status and quotes;
- With help of P2, you can implement @dialogue and display new posts and comments in real time;
- Extend Beta’s Infinite scroll effect and abandon the AJAX page loader.



## Keep the Minutes beta

August 13, 2012

![img](..\assets\ktm_beta-1024x870.jpg)

- Existing slogan Discover and Keep the minutes, so I name the project “Keep The Minutes”;
- Implemented the login and publishing interface of the foreground;
- Refresh-free with Infinite Scroll and Advanced AJAX Page Loader;
- Wptouch pro implements the mobile phone interface;
