# Codce Guess Contest

## Rule

Everyday each person will submit a piece of code. In the first 30 days, the code must be originally written by the submitter. 

不对， 我为何要写英文 = = ！！

重来。 

## 规则 - 提交

每人每天提交一段代码， 最初30天内，代码必须为原创。代码不限制难易，长短。 （这不是为了强迫提升各种语言能力呗）

初期语言选择推荐在以下范畴内：
 
- Html（这个其实不算语言范畴）
- CSS（这个其实不算语言范畴）
- Javascript
- Java
- Python
- PHP

这类语言短期不在使用范畴内: 

- C#
- C++
- Rubys on Rail
- etc


提交的代码可以为单一语种， 即使不能被编译. 
例如: 

```
.nicole { 
background-image: url(https://avatars1.githubusercontent.com/u/38656036?s=460&v=4);
}

```

或者是可以直接被浏览器执行的单一语言:


``` js
var table = require('text-table');
var t = table([
    [ 'master', '0123456789abcdef' ],
    [ 'staging', 'fedcba9876543210' ]
]);
console.log(t);
```

也可以是多种的结合体：

```
-- index.php
-- function.php
-- main.js
-- style.css
```

## 规则 - comment

每次代码提交后，由对方pull后可以自行使用方法编译，或场外求助，或胡乱瞎猜，或文明讲道理~ 在评论区写下这段代码的功能或者特性。

代码创建者可以决定留下些许提示。 

下面是一段实例：


```
<!-- Comment

	# 日期: 2018/08/25 Saturday
	# 创建: Nicole
	# 提示：这是由JAVA写的代码. 
--> 


import static com.kms.katalon.core.checkpoint.CheckpointFactory.findCheckpoint
import static com.kms.katalon.core.testcase.TestCaseFactory.findTestCase
WebUI.openBrowser(GlobalVariable.domain + '/content/ford/master/en_ms/home/text.html')
WebUI.verifyElementPresent(findTestObject('Text Page/SocialShare-Verify'), 0)
WebUI.verifyElementPresent(findTestObject('Text Page/SocialShare-Facebook'), 0)


<!-- Comment

G: （G有一天的时间研究上面的代码）。 打开text 页面并验证两个元素是否存在于DOM中。


N: 答对啦！

-->
```
