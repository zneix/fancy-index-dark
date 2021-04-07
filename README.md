in your `location` directive in nginx config add the following for fancy darkmode:

```nginx
location / {
    fancyindex on;
    fancyindex_css_href "https://cdn.zneix.eu/fancy-index-dark/dark.css";
}
```
