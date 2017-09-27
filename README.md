# Document Injection With Fetch

## makes it easier to do script and html injection

## Example:
```javascript
document.onreadystatechange(
  'https://raw.githubusercontent.com/heyderpd/TRexRunner/master/',
  ['robot.js', 'index.html'])
```