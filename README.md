# Search-Engines ![Icon](https://github.com/trytomakeyouprivate/Search-Engines/blob/main/media/searx-icon.png)
A list of useful Search Engine strings to be used in Firefox and other Browsers. Focus on Privacy, usability, anti-spam and decentralization

- [regular Clearnet Engines](https://github.com/trytomakeyouprivate/Search-Engines/blob/main/Search-Engines.md)
- [TOR Engines](https://github.com/trytomakeyouprivate/Search-Engines/blob/main/Tor-Search-Engines.md)
- [German Search Engines](https://github.com/trytomakeyouprivate/Search-Engines/blob/main/German-Search-Engines.md)

## Why all these Search Engines?

1. We have to rethink the way we use the Web. Instead of just "googling" things, we should think "what do I want to find?" and use the Search engine fitting our needs.
2. Many Search Engines dont support the OpenSearch Protocol, so you can't easily add them to your browser
3. You can't tweak regular OpenSearch engines how you want (special URL parameters)

Using custom search engines in combination with Shortcuts (Firefox Desktop) saves you a lot of time and spares you the Honeypot that Google is, connecting you to everything you need.

Looking for them you can discover lots of sites having an integrated Search engine that is very useful.

### Exceptions

- Some Sites use Javascript to search. You see that, if the URL doesnt change after you enter a search. If this site has no "noJS-alternative", you can't create a custom search Engine of it.
- Chromium-based mobile browsers don't allow you to add a custom search engine. Ditch them!
- Safari mobile does the same afaik, only a very small selection at least including DuckDuckGo
- POST queries are also hard to implement, but should be possible (AddCustomSearchEngine has an option for it in the advanced section)

## How to add them to your Browser

**Falkon**: Settings -> Others -> Manage Search engines

**Firefox Desktop, Librewolf, Tor-Browser**: You need [the addon "Add Custom Search Engine"](https://addons.mozilla.org/en-US/firefox/addon/add-custom-search-engine/), which converts a string to an OpenSearch engine. (Deactivate the Addon afterwards to be sure)

**Firefox mobile**, Brave Desktop: Settings -> Search -> Add Search engine
