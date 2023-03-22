# Hash your email

Change the value of variable `emailToHash` in order to get a hash of your emailimport hashlib;

```python
import hashlib

emailToHash = 'example@mail.com'

hashlib.md5((emailToHash.strip()).lower().encode("utf-8")).hexdigest()
```
