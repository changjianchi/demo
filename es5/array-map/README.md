# array-map

这里的 `map` 不是“地图”的意思，而是指“映射”。 `[].map();`  基本用法跟 'forEach' 方法类似:

```js
[].map(callback,array);
```

`callback` 需要有 `return` 值，如果没有，则循环出来的每个值就会为undefined

```js
[].map(function(value, index, array){
    // value为当前循环的数据
    // index为当前循环的索引，下标为0
    // array为被循环的数组，就是[]
});
```
