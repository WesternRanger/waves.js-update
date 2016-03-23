# waves.js 更新
原有的waves.js 只有attach方法，即只可以给一个input添加效果，却不能移除效果。
该版本新增 detach方法，可以给input卸载添加的效果，参数要跟attach保持一致。
比如：

    Waves.attach('.csbutton', ['waves-button', 'waves-float']);
    
是为 '.csbutton' 增加效果，

    Waves.detach('.csbutton', ['waves-button', 'waves-float']);
    
则是 给 '.csbutton' 去除效果。

waves.js 的使用详情  ![](http://fian.my.id/Waves/)
