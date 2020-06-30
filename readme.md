<image src='screenshot.jpg' align='center' />

## 米字格

> 一个简易创建汉字米字格的css片段



## 如何使用
```html
<!--第一步, 在HTML中引入 css 文件-->


<link rel="stylesheet" href="./main.css">


<!--第二步，编写html代码, 将单个汉字放入如下的html结构中-->

 <div class="ci-box">
    <div class="lt-2rb line"></div>
    <div class="rt-2lb line"></div>
    <div class="rm-2lm line"></div>
    <div class="tm-2bm line"></div>
    <div class="ci">
        <span class="wd">词</span>
    </div>
</div>

<!--第三步, 可选。自定义css样式-->
<style>
    /*设置自定义css样式,  整体宽高, 字体大小*/
    .ci-box{
        width:96px!important;
        height:96px!important;
        margin: 0 2px;
    }

    .ci-box .wd {
        font-size:90px!important;
    }
</style>

```

## license 
MIT

## 作者
[<img src="https://avatars2.githubusercontent.com/u/11222746?s=460&u=768922c8bbecd4c7c745531d9cd41fe1e4e7215c&v=4">](https://github.com/AJLoveChina)