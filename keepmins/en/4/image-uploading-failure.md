# Image uploading failure

Based on the WordPress core, Keep Minutes uses multiple PHP extensions recommended by WordPress for image format conversion and cropping during the process of uploading images. Missing necessary PHP extensions will cause image upload failure.

Extensions that must be installed to run WordPress see： https://make.wordpress.org/hosting/handbook/server-environment/#php-extensions

It is recommended to install PHP 7.4, usually, you need to install the following extensions to meet the basic requirements for WordPress operation:

- fileinfo
- imagemagick
- exif

In addition, for optimizing PHP speed, it is recommended to install the following extensions as well:

- opcache

According to the server’s configuration, choose one of the following database cache extensions to install:

Redis

- redis

Memcache

- memcache
- memcached

After installing the necessary PHP extensions, you can ensure that the pictures are uploaded normally.

The PHP extensions that are currently missing in WordPress can be viewed in the website admin back-end -> Tools -> Site Health. You can complete the missing necessary extensions through the server control panel or contact the server provider to help you with installing.