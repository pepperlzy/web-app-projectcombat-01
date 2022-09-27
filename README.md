# 项目重点

## 头部搜索板块两边固定，中间自适应

> 方法一：采用百分比+浮动
> 方法二：采用定位的方式

## 让一个元素的高度自动和宽度相等

> 给子元设置 padding-bottom: 100%;使其宽度与父元素的宽度相等。


```html
 .box {
        background-color: rgb(255, 164, 46);
        width: 200px;
        height: 100px;
      }
      .item {
        width: 100%;
        /* 与父元素宽度相等 */
        padding-bottom: 100%;
        background-color: rgba(100, 198, 255, 0.4);
      }
    </style>
  </head>
  <body>
    <div class="box">
      <div class="item"></div>
    </div>
```

![1660635948714](https://user-images.githubusercontent.com/109357565/192483455-2cbc148a-057d-4fee-a9ac-bfcc76cde6ab.png)

## 元素默认行高对元素位置调整存在影响

> 给元素设置了默认行高时，在对元素位置的调整上元素行高为设置的字体大小*默认样式的行高，需要计算后进行padding，margin的调整

## 图片宽高不固定，通常将容器宽高固定，图片使用裁剪技术等比放大


## 两个板块内容样式相同时，可以设置相同类名。

## 字体图标占比问题

> 字体图标没有沾满整个容器，测量时测量得到是图片与某个元素的位置，应该与设计师进行沟通后再进行元素的调整。
