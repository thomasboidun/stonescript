# stonescript
External custom script

## how it works

1. Copy/Paste the code below at the top in your MindStone and comment your code. 

```
var domain = "thomasboidun.github.io/"
var path = "stonescript/"
var url = "https://" + domain + path
sys.SetFileUrl(url)

? sys.fileUrl = url
  var lines = [
    "MindStone ready to import stonescript from",
    url
  ]

/*
Your code...
*/
```
