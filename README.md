# image_helper.js

## Usage with npm

```
npm i image_helper.js
```

## Usage with CDN

引入
[https://cdn.jsdelivr.net/npm/image_bind.js](https://cdn.jsdelivr.net/npm/image_bind.js)
以及 [https://cdn.jsdelivr.net/npm/image_helper.js]([https://cdn.jsdelivr.net/npm/image_helper.js)

```js
<script src="https://cdn.jsdelivr.net/npm/image_bind.js"></script>
<script src="https://cdn.jsdelivr.net/npm/image_helper.js"></script>
```
## 接口说明

#### 转换图片的base64

| 参数        | 说明                                                           | 是否必填 |
| ----------- | ------------------------------------------------------------ | -------- |
| target   | 待转换图片的base64                              | 是       |
| success   | 转换回调结果                            | 是       |
```
convertImageByBase64({
        target: '',
        success(res) {
            console.log(res)
        }
    })
```
