# HTML Learning
HTML
## 1、开发环境
## 2、标签语法
## 3、HTML基本骨架
## 4、标签的关系
## 5、注释
## 6、排版标签-标题和段落
## 7、换行和水平线标签
## 8、文本格式化标签
## 9、图像标签
## 10、图片路径
### （1）相对路径
#### ①当前文件
./图片.jpg
#### ②当前文件夹的文件夹
./file/图片.jpg
#### ③上一级文件夹
../图片.jpg
### （2）绝对路径
从本地磁盘出发查找文件:
</br>
①img src="C:\images\mao.jpg">

## 11、超链接标签

①a href="https://www.baidu.com/">跳转到百度</ a>

②a href="#">空链接</ a>

<①a href="https://www.baidu.com/" target="_blank">跳转到百度</①a>

<①a href="./test01.html" target="_blank">跳转到test01.html</①a>

注：其中target="_blank"表示新开一个窗口


## 12、多媒体标签-音频和视频
### 音频
打开控制按钮：<①audio src="./music.mp3" controls="controls">

循环播放：<①audio src="./music.mp3" loop>

自动播放：<①audio src="./music.mp3" autoplay>

注：像loop，control这一类的可以不用写等号后面的内容，注意autoplay在浏览器中一般是被禁用的
### 视频
<①video src="路径"><src>

控制面板：<①video src="路径" controls><src>

循环播放：<①video src="路径" loop><src>

静音播放：<①video src="路径" muted><src>

自动播放：<①video src="路径" autoplay><src>

同理，controls等一般不用写括号后面的内容，注意，当没有muted指令时，autoplay指令也是被禁用的。
## 13、列表
作用：布局内容排列整齐的区域

分类：无序列表（使用最多），有序列表，定义列表

### 无序列表
标签：ul嵌套li，ul是无序列表，li是列表条目
![alt text](image.png)
## 14、表格
## 15、表单
