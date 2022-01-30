# Installing updates

You can choose either auto update or manual update.

## Auto update

- Click “Updates” in dashboard menu
- If there is an update, will show down below in this page.
- Select theme and click “Update”, this theme will be updated automatically.

## Manual update

### Preparation before update

During the theme update, the website will not be accessible. Please do update when the traffic is low.

- Back up your old theme files (can be downloaded via FTP, or downloaded from the command line, back up all the themes under the original themes folder to local or somewhere safe)
- It is recommended to stop the site (this can usually be done in the hosts management panel)
- If you have modified the theme file before, please take a note of the modified file for future operation.

### update

- Delete all old theme files in your site disk space.
- Upload the new theme file to the website space to ensure consistency with the previous directory structure.
- Start up your website, if you are lucky, nothing more you need to do, update is complete

### Pay attention

- If you have used any CDN before, it is recommended to refresh all css and js files in the CDN after the update is complete.
- The theme files that you modified before need to be modified one by one again.
- It is recommended to use the FTP tool for uploading files. It is not recommended to upload the theme with a zip file in the WordPress background.