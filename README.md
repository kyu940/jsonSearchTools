# jsonSearchTools
can do search, sort, and slice of jsonArray.

```javascript
var jsonSearchTools = null;
$(document).ready(function(){
    jsonSearchTools = new JsonSearchTools();
    jsonSearchTools.init([{"title":"1", "create_date":"2019-01-23"},{"title":"2", "create_date":"2019-01-23"},.......]);

    jsonSearchTools.doSearch("Key to search", "keyword", "Key to Sort","asc | desc", startIdx, endIdx, function(selectedItemLength, searchItemList){
        // TODO: your code...
        console.log(selectedItemLength);
        console.log(searchItemList);
    });
});
```
