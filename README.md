# python_note
python note

## Unescape Html characters
```python
import htmllib

def unescape(s):
p = htmllib.HTMLParser(None)
p.save_bgn()
p.feed(s)
return p.save_end()

from http://wiki.python.org/moin/EscapingHtml
```
