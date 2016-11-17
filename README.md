# china-dist-data
中国省市区三级数据（json格式）

## install

```shell
npm install china-dist-data
```


## 数据格式(json)

```js

{
    // 最高级：省份列表
    "-1": [
        {
            "id": "1",
            "code": "110000",
            "name": "北京"
        }
        // ……
    ],
    // 省份下城市列表
    "1": [
        {
            "id": "35",
            "code": "110100",
            "name": "北京"
        }
        // ……
    ],
    // ……
    // 城市下地区列表
    "35": [
        {
            "id": "387",
            "code": "110101",
            "name": "东城区"
        }
        // ……
    ],
}

```
