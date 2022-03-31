# fake-telegram
 telegram fake page

```javascript
// Export

copy(JSON.stringify(JSON.stringify(localStorage)));

```

```javascript
// Import

var data = JSON.parse(/*previously copied stringified JSON from clipboard*/);
Object.keys(data).forEach(function (k) {
  localStorage.setItem(k, data[k]);
});
```