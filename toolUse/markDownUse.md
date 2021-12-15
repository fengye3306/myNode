## docsify框架语法

### 强调内容
适合显示重要的提示信息，语法为 ```!> 内容```
```markDown
!> 一段重要的内容，可以和其他**Markdown** 语法混用。
```
!> 一段重要的内容，可以和其他**Markdown** 语法混用。

### 普通提示
普通的提示信息，比如写 TODO 或者参考内容等。
```markDown
?> _TODO_ 完善示例
```
?> _TODO_ 完善示例

### 忽略编译链接
有时候我们会把其他一些相对路径放到链接上，你必须告诉 docsify 你不需要编译这个链接。 例如：
```markdown
[link](../Utopia/README) 跳转至理想国笔记界面
```
它将被编译为 ```<a href="../Utopia/README" title="title">link</a>``` 并将加载 ```/demo/README.md```  

现在你可以做到这一点
[link](../Utopia/README)  




