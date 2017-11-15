原生分页插件--paging.js

## 引入paging.js 和 默认index.css ##
```
<link rel="stylesheet" href="css/index.css">
<script src="paging.js"></script>
```
##开始插件##
```
var getId = document.getElementById.bind(document)
var data = []
var ulPaging = Paging(data, getId('ul'), getId('div1'))
```
