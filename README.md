# markdownServer

## 文件目录

* ./markdowns/* 存放需要解析的markdown文件
* ./templates/* 存放工程需要的html模板

## 接口

* / index显示扫描到的文件列表
* /read?file=${fileName} 显示markdown转换后的HTML页面
* /update 调用后，重新扫描文件目录
