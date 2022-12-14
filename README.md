# Library of Congress bibframe2marc transformation
It's all in the index.html

With thanks to the  Network Development and MARC Standards Office for https://github.com/lcnetdev/bibframe2marc code development and maintenance. :)

### The compiler

This project comes with a compiled version of the stylesheet. If you
make changes to it, you can compile it with `xslt-3` as follows:

```
node node_modules/xslt3/xslt3.js -t -xsl:xslt/main.xsl -export:main.sef.json -nogo "-ns:##html5"
```

You can also compile it with Saxon EE, if you prefer.
