<<<<<<< HEAD
# myamap

A new flutter plugin project.

## Getting Started

This project is a starting point for a Flutter
[plug-in package](https://flutter.io/developing-packages/),
a specialized package that includes platform-specific implementation code for
Android and/or iOS.

For help getting started with Flutter, view our 
[online documentation](https://flutter.io/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.
=======
myamap 是基于flutter准备封装的一个插件，当然这是你想自己倒腾，如果你觉得麻烦可以去搜索别人写好的插件直接使用，我是啥子都想自己试一试，欢迎交流

【myamap】为什么取这个名字哈，还是解释下，我的账号基本都是以“my”开头，所以涉及到相关项目的时候我会用这个命名

该demo主要是做了一个Flutter基础布局，涉及通讯录，列表，搜索，登录
[在线案例](https://github.com/mymaizi/flutter_hello_world)

### 可能会遇到的问题

* 包引用（建议跟着高德地图官网一步一步的去做）
* 关于引入so文件后出错，建议看错误提示，一般会提示couldn't find "libflutter.so"文件，建议看下这条错误的具体信息，删除对应的so文件即可
* 切记这是重点在高德api文档中明确指示（需要onCreate重写）那么想办法把对应的参数传递过来即可，这个时候就会涉及更改flutter生成的文件，里面提示不要修改，但是我目前没找到好的方式去获取这个参数
>>>>>>> 0e8988f2d5996fe837286fa0892e625f87802d86