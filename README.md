
##how to get guage data

```javascript
  var data = JSON.parse(localStorage.getitem("gauge_data"))
```
## structures

```javascript
  {"IN":[{"x1":float,"x2":float,"y1":float,"y2":float,"position":String}...],
    "OUT":[{"x1":float,"x2":float,"y1":float,"y2":float,"position":String}...],
    "INTI":{"x1":float,"x2":float,"y1":float,"y2":float,"w":float,"d":float},
    "scale":float
  }
```
