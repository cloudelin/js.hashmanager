js.hashmanager
==============

Javascript utility for manage the URL hash and event

### New manager object

```
var hashmanager = $.hashmanager();
```

### Register handler

```
hashmanager.registerHandler('viewContent', function(data){
  // run something
});
```

### Push hash (window.location.hash)

```
  var data = {};
  data.action = 'viewContent';
  data.contentId = contentId;
  hashmanager.push(data);
```
