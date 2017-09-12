# JavaScript [学习路径图](http://www.runoob.com/js/js-tutorial.html)

	简介：JavaScript目前拥有十分广泛的应用市场,从前端到后台到移动端都有JavaScript的影子.

![.js](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1502362556655&di=75e8e85c7a65c2ab4c0c449788678409&imgtype=0&src=http%3A%2F%2Fs5.51cto.com%2Fwyfs02%2FM02%2F8C%2FC0%2FwKioL1h3KO2wDLl_AADTxc8C9A8345.jpg "JS炫酷logo")


## 示例代码：详细代码看项目内文件
* MyFirstJavaScriptDemo.html 我的第一个JavaScript示例程序<!DOCTYPE html>
```JavaScript
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8"> 
<title>示例程序核心代码</title> 
<script>
function myFunction(){
	document.getElementById("demo").innerHTML="我的第一个 JavaScript 函数";
}
</script>
</head>
<body>

<h1>我的 Web 页面</h1>
<p id="demo">一个段落。</p>
<button type="button" onclick="myFunction()">点击这里</button>

</body>
</html>
```

## 代码简介
|文件编号|文件创建日期|文件名|文件中文翻译|文件知识点|知识点掌握程度|
|---|---|---|---|---|----|
|1|2017.08.10|MyFirstJavaScriptDemo.html|我的第一个JS示例|html内嵌js代码|+++++|

## 进度
|日期|名称|进度|
|---|---|---|
|2017.08.11 11.26| JavaScript基础语法| 90%|

## 笔记
### 2017.08.10 JavaScript用法 body中标签、head中标签、外部JS +++--
* body中的js
```JavaScript
<body>
<script>
document.write("<h1>这是一个标题</h1>");
document.write("<p>这是一个段落</p>");
</script>
</body>
```
* head中dejs
```JavaScript
<head>
<script>
function myFunction()
{
    document.getElementById("demo").innerHTML="我的第一个 JavaScript 函数";
}
</script>
</head>
```
* 外部js
```JavaScript
<!DOCTYPE html>
<html>
<body>
<script src="myScript.js"></script>
</body>
</html>
```

### JavaScript输出
* windown.alert(); -> 弹出警告框
``` window.alert(5 + 6); ```
* document.write(); -> 文件写入HTML文档
``` document.write(Date()); ```
* innerHTML -> 写入到HTML元素
``` document.getElementById("demo").innerHTML = "段落已修改。"; ```
* console.log() -> 写入到控制台
``` console.log(666); ```

### JavaScript基础语法
* 字面量  
	* 数字：整数、小数、科学计数
	* 字符串：'王家伟' "技术大牛"
	* 表达式字面量：5 + 6
	* 数组字面量：[1, 2, 3, 4, 5]
	* 对象字面量：{"姓名": '王家伟', "年龄": "24"}
	* 函数：function myFunction(a, b) { return a * b; }
* 变量：var x, y x = 5 y = 6
* 操作符：* / + - = >= <= != 
* 语句：x = 5 + 6； y = 1 + 2;
* 关键字：var等
* 注释：```//注释描述```
* 函数：
* 字母大小写
* 字符集



> 本代码工程由`王家伟`先生创建维护

>> ***崇拜的目光接踵而来***

> 该Git使用代码绝大多数拷贝自RUNOOB.COM

- [x] 姓名：王家伟
- [x] 年龄：24 
- [x] 工龄：3
- [ ] 其它：null

* U•ェ•*U
	* ( *︾▽︾)
		* ╮(╯▽╰)╭

[重点知识](#笔记)

# <del>Javascript已看完</del>
