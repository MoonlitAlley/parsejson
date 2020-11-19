# parsejson
parse json from a dot format

- input
```
{"aaa.bbb.ccc":1, "xxxx.a":"first", "aaa.bbb.yyyy.0":"tesrt", "aaa.bbb.yyyy.1":false}
```

- output
```
{"aaa":{"bbb":{"ccc":1,"yyyy":["tesrt",false]}},"xxxx":{"a":"first"}}
```

relate
https://github.com/cthulhu/jsonpath

