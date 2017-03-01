# Readme
 
## 通知
分支 devlope 

格式: 项目名称 总结(可分享的内容)+ 待解决问题

## 主页

## product 页面

### 总结

1. flex 布局 和 定位 @media
2. 优化了动画的滚动监听
3. 触发浏览器的滚动监听
4.  `<meta http-equiv="X-UA-Compatible" content="IE=edge">`   IE以最高模式渲染
5.  `<meta name="renderer" content="webkit">` 浏览器默认使用 webkit 渲染 用于多核浏览器
6. 动画全部使用落空类

### 问题
1

``` js
 /* 跨域 ,看不到源码*/
var _hmt = _hmt || [];
(function () {
   var hm = document.createElement("script");
   hm.src = "//hm.baidu.com/hm.js?d78ef535aafb3c812f8d4a6c2b753261";
   var s = document.getElementsByTagName("script")[0];
   s.parentNode.insertBefore(hm, s);
})();
```
2

```js
// kf5 调用第三方插件
    if (typeof window.KF5SupportBoxAPI != 'undefined') {
        var supportBox = window.KF5SupportBoxAPI;
        supportBox.ready(function () {
            supportBox.removeButton();
            $('#tool-serviceBtn').click(function () {
                supportBox.open(function () {});
            });
            $('#footer-serviceBtn').click(function () {
                supportBox.open(function () {});
            })
        });
    }
```
3 缩小后右上角的btn 

## help




