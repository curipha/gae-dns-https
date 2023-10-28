DNS-over-HTTPS front-end on App Engine
====================
A front-end for DNS-over-HTTPS with Google Public DNS / Cloudflare Resolver hosted on Google App Engine.

https://dns-https.appspot.com/

Deploy
--------------------
```bash
git clone https://github.com/curipha/gae-dns-https.git
cd gae-dns-https/
gcloud --quiet app deploy --no-cache
```

Icon
--------------------
`dns.png` is originally distributed at [Material icons](https://fonts.google.com/icons?selected=Material%20Icons%3Adns%3A) under the Apache License Version 2.0.

`www/favicon.ico` is created from `dns.png`.
