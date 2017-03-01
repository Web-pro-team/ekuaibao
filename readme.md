# Readme
 
## 备注
分支 devlope 
readme格式: 项目名称 总结(可分享的内容)+ 待解决问题
自己的文档中,已解决的问题,和待解决的问题,加点注释

## index

## product

### 总结

1. flex 布局 和 定位 @media
2. 优化了动画的滚动监听
3. 触发浏览器的滚动监听
4.  `<meta http-equiv="X-UA-Compatible" content="IE=edge">`   IE以最高模式渲染
5.  `<meta name="renderer" content="webkit">` 浏览器默认使用 webkit 渲染 用于多核浏览器
6. 动画全部使用落空类
7. 跨域加载js

### 问题

1

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
2 缩小后右上角的btn 

## more

## help 

## footer

## login



