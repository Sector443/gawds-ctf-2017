# Cipher [30pts]

Some ciphers are too easy to break, Can you crack this ?
fhdvhu flskhu lv wrr hdvb wr fudfn

Note: Answer is md5 hash of the decoded text, that is flag{md5(decoded-text)}


### Solution

String seems to be in ROT cipher. We will use easily available online tool for key rotation attack to find out meaningful text

http://theblob.org/rot.cgi?text=fhdvhu+flskhu+lv+wrr+hdvb+wr+fudfn

**ROT-23: ceaser cipher is too easy to crack**

and as per asked in question we have to convert our string to md5 hash

```python
>>> import hashlib
>>> hashlib.md5(b'ceaser cipher is too easy to crack').hexdigest()
'26802ab441ba6d56cf914480171521d6'
```

So our flag will be

flag{26802ab441ba6d56cf914480171521d6}
