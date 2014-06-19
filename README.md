# divclip

Extricate element from DOM by selector  

derived and augmented from htmlclipper by Florentin Sardan

- ES5 compliant
- scoped CSS
- use external SHA256
- convert relative a href to absolute URL
- wrapped for browserify/require()




# example
``` js
var divclip = require("divclip");
var html    = divclip.bySel(".article-body");
console.log(html);
```

https://www.npmjs.org/package/divclip  
Tested with NodeJS 0.10.28 and Firefox30+


# references
* [htmlclipper](https://github.com/florentin/htmlclipper) by Florentin Sardan
* [SnappySnippet](https://github.com/kdzwinel/SnappySnippet) by Konrad Dzwinel
* https://stackoverflow.com/questions/4911338/tools-to-selectively-copy-htmlcssjs-from-existing-sites


