### 发现一个逆天的问题(文档中没有说明的问题)

```
<option selected=false>大连市</option> <!-- 这样也可以 -->
<!--<option selected=null>大连市</option>--> <!-- 这样也可以 -->
```

```
<!--篮球：<input type="checkbox" name="hobby" value="basketball" checked=false>--> <!-- 这样也可以 -->
篮球<input type="checkbox" name="hobby" value="basketball" checked=null> <!-- 这样也可以 -->
```

详见示例代码。

一个哥们儿无意间发现的，是不是要说些什么！

