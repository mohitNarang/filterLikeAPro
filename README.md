# filterLikeAPro
This repository contains examples about filtering html. I hope to keep adding new filtering examples based on usage or questions in issues. 

If browsing through a search engine with results which are ads in the beginning of results, it might be possible to filter them with normal css selectors in various filters such as ubo etc. 
eg. 
``` CSS
when trying to block an ad item which might have a li element that needs to be hidden, it can be done by 
css filter. 
searchengine.com##li -> will block every li element from the HTML page

searchengine.com##li[data-layout="ad"] -> will block every li element, that has data-layout="ad" set in its definition
```

