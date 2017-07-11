# Photo Selector

html + css + jquery 仿微信上传图片界面及功能。

使用了weui，当然也可以不用。

## 预览
需在手机上或浏览器手机模式下预览。**浏览器若调至手机模式下显示不正常刷新即可**

预览地址：[https://kinice.github.io/Photo-Selector/](https://kinice.github.io/Photo-Selector/)


## Usage

按照index.html中写的，引入相应资源。

配置config。

```
 var config = {
     maxCount: 18,                        //最大可选择数量
     setCount: 0,                         //已经选择了的数量。可选择的数量为(maxCount-setCount)。
     //container: '.img-con',             //外层容器。不用管，也不用写。有特定需求的话可以加上。
     //selectContainer: '.f-select-con'   //选择用的小对号的容器。同上。
 }

 var photo_select = new photoSelect(config)

 // 选择完以后
 console.log(photo_select.selectResult)   //即可查看选择的图片路径Array。

```
