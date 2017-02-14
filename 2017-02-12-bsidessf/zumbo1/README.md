#Zumbo 1
```
Welcome to ZUMBOCOM....you can do anything at ZUMBOCOM.

Three flags await. Can you find them?

http://zumbo-8ac445b1.ctf.bsidessf.net

Stages 2 and 3 - coming soon!
```

Okay, we have colorful css theme /index.template
In source code it have the hint
```
<!-- page: index.template, src: /code/server.py -->
```
If I open /code/server.py, then an error message appears.
```
[Errno 2] No such file or directory: u'code/server.py'
```
I just opened /server.py and it contains code.
First flag it's just a string:
```python
flag1 = 'FLAG: FIRST_FLAG_WASNT_HARD'
```
