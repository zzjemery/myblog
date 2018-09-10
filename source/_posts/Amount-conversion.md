---
title: 金额转换问题解决
---

## 将金额去除逗号

```
    function(value){
        return value.replace(new RegExp('\,',["g"]),'');
    }
```