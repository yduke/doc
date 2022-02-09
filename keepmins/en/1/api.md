# API

Since V 2.9.6.4, Keep Minutes theme helps people create, share, publish their contents more faster by providing an API.

Assume that the URL of your Keep Minutes theme website is: https://keepmins.com/

**API Endpoint:** https://keepmins.com/ (Same as your website URL)

**API parameters:**

`kmtitle` The title

Example: `https://keepmins.com/?kmtitle=The Title Text`

 

`kmcontent` The content

Example: `https://keepmins.com/?kmcontent=the content texts you want`

 

`kmimage`  The image

Example: `https://keepmins.com/?kmimage=the-URL-of-a-image`

`kmtag` The tag(s)
Example:`https://keepmins.com/?kmtag=tag1,tag2,TAG3`

You can surely use these parameters with combinations.

Example:

```
https://keepmins.com/?kmtitle=The Title Text&kmcontent=The content texts you want&kmtag=tag1,tag2,tag3
```

 

Access the endpoint with parameters, if you have the publishing permission of the target site, all parameters will be automatically filled into the post form, all you have to do is click “send”.

This API only provides a way to quick input, you have to publish them manually.