---
id: digitalocean
title: DigitalOcean
---

An easy way to host and manage servers. DigitalOcean is the first VPS provider
I've used. If I need a server quickly and without fear of billing, I choose
DigitalOcean.

## Droplets

DigitalOcean names their servers as `droplets`, kindof like heroku names theirs
as `dynos`, although they are not comparable.

## Spaces

Spaces is a quick-and-dirty way to host data in an object storage. Quite
interestingly, it's advertised[^1] as a way to host your web assests, such as
images, css, and javascript, but on the other hand, they tell to avoid[^2] small
files under 20MB in size as it's more performant to host larger files.

The performance gains for small web assets in the kilobytes is probably 
negligible.



[^1]: https://www.digitalocean.com/products/spaces/
[^2]: https://www.digitalocean.com/docs/spaces/resources/performance-tips/#file-size