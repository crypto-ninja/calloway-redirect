# calloway-redirect

Redirects the bare domain `callowayproperty.co.uk` (and every path on it) to `https://www.callowayproperty.co.uk`, served by GitHub Pages because the bare domain's DNS cannot point a CNAME at the site.
It holds nothing but that redirect: `index.html` and an identical `404.html`, so deep links keep their path.
It retires in June 2027, when the domain moves to Cloudflare and the bare domain can be served there directly.
