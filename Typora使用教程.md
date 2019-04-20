# Typora的markdown语法

#### 1.标题

 `CTRL` + `数字键`



#### 2.下划线

 `Ctrl` + `U` 

<u>这是下划线</u>



#### 3.删除线

 `Alt` + `Shift` + `5`

~~这是删除线~~



#### 4.字体加粗

`Ctrl` + `B`

**这是加粗字体** 



#### 5. 字体倾斜

`Ctrl` + `I`

*这是倾斜字体* 



#### 6. 无序列表

`Ctrl` +  `Shift` + `]`（可以嵌套`无需/有序`列表）

- 1
- 2
  - 3
    - 4



#### 7.有序列表

`Ctrl` +  `Shift` + `[`

1.  
2.  
   1.  
   2.  
      1.   
      2.  



#### 8.引用

`Ctrl` +  `Shift` + `Q`

> 这是引用



#### 9.插入链接

`Ctrl` +  `K`  

[百度](<https://www.baidu.com>)



#### 10.插入图片

本地直接拖拉图片到 `md` 文件 或者配合 `MPic`完成图片上传图床并复制链接到 `md` 文件（推荐）或者 `Ctrl` + `Shift` + `I`  （这张图片是抓取QQ空间登录页背景图，可能会挂掉。）

![抓取QQ空间图片](<https://qzonestyle.gtimg.cn/qzone/qzactStatics/imgs/20171122191603_896cd9.jpg>)



#### 11.代码块

`Ctrl` + `Shift` +`K` 效果如下

###### **Python**

```python
import requests
response = requests.get("http://www.baidu.com/") 
print response.text
```

###### **C**

```c
#include <stdio.h>

int main() {
    
    printf("hello world!\n");
    
    return 0;
}
```



#### 12.文章跳转

`Ctrl` + `Home` 跳转至文章开头，`Ctrl` + `End` 跳转至文章末尾



#### 13.选中英文单词/中文

`Ctrl` +` D` 或者 `Ctrl` +` Shift` +` left/right` 左右进行文本选中



#### 14.替换

`Ctrl` + `H` 



#### 15.表格

`Ctrl` + `T` 快速生成表格



#### 16.着重关键字

`Ctrl` + `Shift` +`~`

`关键字效果`



#### 17.分割线

`-` `-` `-` + `Enter`

---



#### 18.高亮显示

==高亮显示 ==

==高亮显示== 



#### 19段落快捷键

`Ctrl` + `0` 



#### 20定义脚注

文字[ ^脚注]

文字[^我是脚注]

[^我是脚注]: https://baidu.com



#### 21.toc快速生成目录

`[toc]` + `Enter` 

[TOC]

