/*
Title: previewImage
Description: previewImage
*/

# 功能描述
previewImage是仿wx.previewImage的原生js实现，支持图片预览，滑动切换，双指缩放，图片缓存

# 依赖模块
无

# 快速使用

```js
var obj = {
    urls : ['img/1.jpg','img/2.png','img/3.png'],
    current : 'img/1.png'
};
previewImage.start(obj);
```

## 配置项

### urls
* 类型：Array
* 默认值：null
* 作用：预览的图集路径
* 是否必传：是
### current
* 类型：String
* 默认值：none
* 作用：当前预览的图路径
* 是否必传：是

## 方法
### 查看
```js
previewImage.start(obj)
```

# 特别说明
更多配置和用法，请参考examples/index.html