# kagiso_sitemap
A paged sitemap for Wagtail.

## Installation
`pip install kagiso_sitemap`

Add `kagiso_sitemap` to your `INSTALLED_APPS` in your `settings.py`.

Add the following to `urls.py`:
```py
from kagiso_sitemap import urls as kagiso_sitemap_urls


url(r'', include(kagiso_sitemap_urls)),
```

## Running the tests
```
py.test
```
