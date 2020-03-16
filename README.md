# Token generator for Bakalari API
Jednoduchý Python script pro vygenerování tokenu pro Bakaláři API.

Doporučuji: [xmlcurl](https://github.com/mariansam/scripts/tree/master/xmlcurl)

## Návod
Script chce tři argumenty - doménu serveru Bakalářů, uživatelské jméno, heslo. Příklad:

### Python 2
Not supported anymore, if you're really that **boomer**, checkout commit [`c555ec`](../../tree/c555ec15e7a767ebd55c9a3022a07d4633977fcd).

### Python 3
```sh
./mktoken3.py bakalari.gjp-me.cz jannovak honzovosilnyheslo
```

Skript vždy vygeneruje token ke dnešnímu datu.

**Skript jde použít i jako modul.**

Python 2:
```python
import mktoken
token = mktoken.generate_token('bakalari.gjp-me.cz', 'jannovak', 'honzovosilnyheslo')
```

Python 3:
```python
import mktoken3
token = mktoken3.generate_token('bakalari.gjp-me.cz', 'jannovak', 'honzovosilnyheslo')
```
