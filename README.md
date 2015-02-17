# gulp-kill-semicolon

```npm install gulp-kill-semicolon```

How often did this happen to you?
```javascript
var s = 'hello;'
```
Or this?
```javascript
var o = {
		h: 'world,'
	}
```
(If you still didn't notice, then you might already have this problem somewhere else - it's either semicolon or colon accidentally included INSIDE the string - within the quotes!)

Did you spend hours on searching for what was wrong with your code? No IDE showed you that there was something wrong..

Well, suffer no more, as here come gulp-kill-semicolon.