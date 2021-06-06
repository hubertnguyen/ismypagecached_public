# Is My Site Cached (.com) Official Page
[ismypagecached.com](http://ismypagecached.com/) detects your "page caching" configuration and current state. The goal: to save you a little bit of time 😇

We try supporting as many page-caching systems as can be detected. Feel free to report issues and add feature requests. 
When reporting an issue, we need:
1. Description of the issue
2. Link for testing

<img src="https://github.com/hubertnguyen/ismysitecached_public/blob/main/ismypagecached-screenshot.jpg" width="300">


## Supported page caching, by levels
There are multiple places where page caching can happen, and the tool tries to differentiate between them, because there can be technical implications or flags from that.
### Plugin (PHP code)
- Flying Press
- W3 Total Cache
- WP Fastest Cache
- WP-Rocket
- LiteSpeed Cache
### web-server
- Kinsta Cache
- LiteSpeed cache
- NINGX SRCache
- NGINX x-proxy
- Runcloud Cache
- Siteground (needs testing)
- Varnish
- Wordpress.com
### CDN
- Amazon Cloudfront 
- Cloudflare (+APO)
- Fastly
- QUIC.cloud
- Generic Varnish-based CDNs
