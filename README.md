# keyboard_Cash
Android自定义收银键盘(原创)

效果图：

![key](https://github.com/javaexception/keyboard_Cash/blob/master/app/src/main/res/raw/key.gif)<br>

最近开发项目需要自定义收银键盘，网上查了查都感觉不是太好，于是自己写了一个，自定义的键盘主要是根据GridView+EditText结合来写的<br>
        

 然后自己写了一个PayKeyAdapter，设置了键盘的文字和类型。并且设置适配器
  final PayKeyAdapter adapter = new PayKeyAdapter(this);
        gridview.setAdapter(adapter);
        
核心的语法在GridView的setOnItemClickListener事件.具体算法就不贴上了，直接下载源码就可以了.<br>
键盘的高度适配的话，修改PayKeyAdapter里的item布局，我布局里面有标出。

[CSDN](http://blog.csdn.net/qq_34908107)<br>
[简书](http://www.jianshu.com/p/a57f32c21fb7)<br>

我的公众号如下<安卓干货铺>:<br>
![Alt text](https://github.com/javaexception/keyboard_Cash/blob/master/app/src/main/res/raw/asdas.jpg)<br>
