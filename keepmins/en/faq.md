# Frequently Asked Questions

### It says “Looks like you are not connected to the server. Keep Minutes could not connect with server.”

This is often caused by a Permalink change, and sometimes this problem occurs when you upgrade WordPress or install a plugin. The solution is very simple. In the WP admin => Settings => Permalink, Just click Save Changes. The fixed link is refreshed and the function returns to normal.

### My interface has become a full Chinese version!

The theme will automatically switch depending on “WordPress Site Language” setting. If your WordPress Admin panel “Site Language” is set to English, the theme interface language will switch to English. Please select your language when installing WordPress.

Switch language setting location: Back end Admin – Settings – Site Language

### Can’t get my location info

Check three aspects:

1 Whether the website is configured with SSL encryption(https access), whether the whole site resources are https;

2 When the browser asks if the location permission is allowed, you should click “Yes”;

3 If the KEY of the map service is filled in correctly, see [the pre-preparation to get the key part](https://doc.dukeyin.com/keepmins/zh/preinstall/).

 

### Unable to post

This issue will occur on two kind of site:

1. WordPress has not been updated, staying in version 4.7 or 4.7.1. It has been confirmed that these two versions limit the theme to output article feed, resulting in no feed information at the time of publication so that the publication fails.
2. Some “optimize plugins” improper settings, shielding the theme of the feed generated.

Solution:

- Update WordPress to the latest version.
- Remove your optimization plugin. The “CND Enabler” plugin is recommended for CDN.

Finally in the WordPress admin panel -> Settings -> Permalink -> don’t change anything, click Save Changes. Update the permalink.

This setting will solve this problem, and the posting will return to normal. If your problem persists, please do it again from the first step. The permalink part is a must.

### https prompts “not a secure connection” on the browser

This is because your website references http resources outside the site. https needs to be “whole site” https, images, style sheets, js all. Check the plugins you installed, your statistics code or other things that may be loaded outsite the main website. Whether the resource has http unencrypted, remove it, problem solved.



More FAQs:

- [Upgrading V2.7 to V2.9](4/2-7to2-9.md)
- [Gravatar](4/gravatar.md)
- [Image uploading failure](4/image-uploading-failure.md)
- [Authorization and activation](4/authorization.md)