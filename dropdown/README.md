# css3下拉测试

```js
.btn{width: auto; height: 40px; line-height: 40px; text-align: center; background: #000; color: #fff; padding: 0 5px; border: 1px solid #fff;}
.demo{width: 300px; max-height: 0; overflow: hidden; border: 3px solid #f00; background: #fff; line-height: 24px; transition: max-height 2s; -webkit-transform: translateZ(0); -moz-transform: translateZ(0); -o-transform: translateZ(0); transform: translateZ(0);}
.active{max-height: 500px;}

$('.btn').on('click',function(){
    $('.demo').addClass('active');
});
```
没感觉出来开了gpu有啥区别，求赐教
