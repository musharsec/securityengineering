#<b> Security Engineering </b>

This is my braindump for things related to security engineering 

Appending random hex string to domain;

``` 
s = "sub."
d = ".a.evilcorp.com"

for i in range(256):
    print(s + ("{:02x}".format(i)) + d)`
```
