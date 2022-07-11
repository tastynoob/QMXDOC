# 文档说明


## 如何添加自己的文档(仅限开发人员)
 首先在仓库中修改"_sidebar.md"文件       
 添加自己文档的引用
 比如自己在目录"测试"分支下新建文档"开始学习"   
 那么需要添加"_sidebar.md"内容如下
```
    * 测试
        * [开始学习](md/start.md)
```
 其中md/start.md即在文档仓库下md文件夹内的start.md文件,格式为markdown
 文件可自由编写     
 如果要在markdown内引用图片     
 可使用     
```
 [图片名称](image/图片文件名)
```