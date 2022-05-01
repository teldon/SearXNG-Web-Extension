# SearXNG-Web-Exstension (Unofficial)
**SearXNG** is a free Internet metasearch engine that aggregates results from various search services and databases. Users are not tracked or profiled.

SearXNG is a fork of <a href="https://github.com/searx/searx"><b>SearX</b></a>

<a href="https://github.com/searxng/searxng"><b>SearXNG</b></a> - Original repository on GitHub

# How does it work? 
Extension use ``manifest.json`` settings which change your main search engine. 

Example: 
```
https://example.com/search?q={searchTerms} --> https://searx.be/search?q={searchTerms}
```
it means that your browser starts to use second link when you make search request.

# Tricks
If you want use **SearXNG** as support to main search engine do this:
- add this addon into your browser 
- agree when browser shows you "Add this extension?"
- disagree when browser shows "Do you want change your main search engine?" 
- use keywords like ```@searxng, @searx, @sx``` if you want use **SearXNG** when you make request

# Contributors
[**Rodion Borisov**](https://github.com/vintprox) - found ```"suggestion_url"``` and etc

[**Ivan Muzyka**](https://github.com/SeryiBaran) - found icons and etc
