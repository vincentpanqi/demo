# JSON.parse

```js
/**
 * @file 解析为json对象
 * @author xiaowu
 *
 * @description 同eval,new Function不同的是，该解析很严格，必须符合json要求
 * @param {string} str 要解析的字符串，如果不是一个规范的字符串将抛错
 * @return {Object} 解析后的对象
 * @example
 *     JSON.parse(str);
 */
```

## 兼容性

兼容 `ie9+` ，[link](http://kangax.github.io/compat-table/es5/#test-JSON)