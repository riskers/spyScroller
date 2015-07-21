# 监测指定元素的滚动距离

![ex](http://gyb-demo.qiniudn.com/15-7-21/31882543.jpg)

# 使用
```js
    $('body').spy({
        'spyElements' : ['#reward','#pro','#explanation','#pgy'] ,
        'spying' : function(i,top){
            $('.links').find('a').eq(i).addClass('cur')
                .siblings().removeClass('cur')
        }
    })
```
