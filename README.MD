Upscuits data container
=======================

This create a data containers with upscuits data.

Usage
-----

```
FROM thibautgery/upscuits

ADD config.js /var/www/status/js/config.js

VOLUME /var/www/status
```

Config your status page and use the volume from apache or Nginx
