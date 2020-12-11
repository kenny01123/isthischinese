# ischinese
ischinese is an utility package for you to know if some word is Chinese

# Setup
1.　run <npm i isthischinese> in your terminal after <npm init>.
2.　in your javascript file, put <var chinese = require("isthischinese");>

# Usage 
You can test if a string contains Chinese like this:

```
var chinese = require("isthischinese");
var string = "你好，世界";
console.log(chinese.isChinese("is it Chinese??"));
//console prints "nah"
console.log(chinese.isChinese("string"));
//console prints "yes it is chinese.これは中国語です。"
```
# contact
made by Kenny Ng, who knows Chinese.
if you have any question, contact me at contact@kennyng.dev.