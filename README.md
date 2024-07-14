# stonescript
External custom script

## how to use

1. Restart game.
2. Open Mind Stone and copy/paste the code below above your code. 

```
var domain = ＂thomasboidun.github.io/＂
var path = ＂stonescript/＂
var url = ＂https://＂ + domain + path
sys.SetFileUrl(url)
? sys.fileUrl = url
  loc.Leave()

// import Ping
```
3. Comment your code.
```
var domain = ＂thomasboidun.github.io/＂
var path = ＂stonescript/＂
var url = ＂https://＂ + domain + path
sys.SetFileUrl(url)
? sys.fileUrl = url
  loc.Leave()

// import Ping

/*
// Logic code...
? item.potion = "healing" & hp < 20
  activate potion
*/
```
4. Close Mind Stone and explore any location. The previously pasted code will make you exit the location automatically after changing the file URL.
5. Reopen Mind Stone. Remove the logic code for change file URL and uncomment the `import Ping` line.
```
import Ping

/*
// Logic code...
? item.potion = "healing" & hp < 20
  activate potion
*/
```

