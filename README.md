# RTMPLive的使用

## 启动

目前只支持windows系统，直接点击RTMPLive.exe文件启动,会出现一个命令行窗口，不能关闭这个窗口

![image](https://github.com/tsingsee/RTMPLive/blob/master/images/start.png)

## 查看

直接在浏览器输入：[localhost:9600/index.html](http://localhost:9600/index.html)

![image](https://github.com/tsingsee/RTMPLive/blob/master/images/list.png)

## 操作

第一次运行打开界面列表应该是没有数据的，我们根据自己的需求新增数据

### 新增

在新增界面我们只需要填写三个参数：名称，源地址，推流地址

其他参数默认即可，当然我们可以根据自己的需求来配置参数

![image](https://github.com/tsingsee/RTMPLive/blob/master/images/add.png)

### 修改、删除

新增数据之后主界面的列表就会有我们新增的数据，在列表中操作一列有修改和删除按钮

当我们相对那条数据进行修改和删除操作，只需要在点击那条数据对应的修改和删除按钮即可

![image](https://github.com/tsingsee/RTMPLive/blob/master/images/edit.png)

![image](https://github.com/tsingsee/RTMPLive/blob/master/images/delete.png)

### 查询

在主界面的搜索框输入会匹配我们列表中的名称字段的值，当列表中数据过多的时候可以很方便我们快速找到我们想要找的那条数据

当我们在搜索框输入1的时候，因为我们列表中有一个名称为test1的数据，这条数据就会被匹配到，显示在列表中

![image](https://github.com/tsingsee/RTMPLive/blob/master/images/search0.png)

当我们在搜索框输入2的时候，因为我们列表中没有一个名称中带有2的数据，没有数据被匹配到，列表中就一条数据都不会显示

![image](https://github.com/tsingsee/RTMPLive/blob/master/images/search1.png)

### 获取更多信息

TSINGSEE青犀开放平台：[http://open.tsingsee.com](http://open.tsingsee.com)

Copyright © TSINGSEE.com 2012~2019