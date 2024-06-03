### h5 图片预览 （官方的文档地址已经找不到了，要看就看我这个demo吧）

#### 介绍
previewImage.js 实现的移动端图片的预览，缩放功能，官方下载链接：https://www.apicloud.com/mod_detail/previewImage

### 功能描述
previewImage是仿wx.previewImage的原生js实现，支持图片预览，滑动切换，双指缩放，图片缓存

### 快速使用

```js
var obj = {
    urls : ['img/1.jpg','img/2.png','img/3.png'],
    current : 'img/1.png'
};
previewImage.start(obj);
```

### 配置项

#### urls
* 类型：Array
* 默认值：null
* 作用：预览的图集路径
* 是否必传：是
#### current
* 类型：String
* 默认值：none
* 作用：当前预览的图路径
* 是否必传：是

### 方法
#### 查看
```js
previewImage.start(obj)
```

### 注意事项
* 直接放在head中引用可能会出现appendChild错误的信息啥的，遇到这个问题不要慌，给它换到body中即可完美解决
