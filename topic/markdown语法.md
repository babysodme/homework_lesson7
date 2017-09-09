# h1
## h2
### h3
#### h4 
##### h5
###### h6

## 标题Markdown常用语法 

# 表格

代码块|超链接|图片|标题|有序列表|表格
---|---|---|---|---|---
代码块|超链接|图片|标题|有序列表|表格


1.新生大学
2.Javascript
3.编程入门

> ## 这是一个标题。
> 
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");

列表

*   Red
*   Green
*   Blue

1.  Bird
2.  McHale
3.  Parish

+   Red
+   Green
+   Blue

-   Red
-   Green
-   Blue

分割线

* * *
1
***
2
*****
3
- - -
4
---------------------------------------


连接

This is [an example](http://example.com/ "Title") inline link.

强调

*single asterisks*

_single underscores_

代码

可以用反引号把它包起来（`）


`fetchDatawords: function () {
        var wordsList = [];
        axios.get('https://js.xinshengdaxue.com/api/v1/learnJS/course/1/words')
          .then(function (response) {
            wordsList = response.data.words;
            (function (arr, len) {
              arr.sort(function () { return Math.random() - 0.5; });
              var a_len = arr.length;
              var result = [];
              for (var i = 0; i < a_len; i += len) {
                result.push(arr.slice(i, i + len));
              }
              app.wordsList0 = result[0];
              app.wordsList1 = result[1];
              app.wordsList2 = result[2];
              app.wordsList3 = result[3];
            })(wordsList, wordsList.length / 4);
          })

          .catch(function (error) {
            console.log(error);
          });`

图片 

[名称]: url/to/image  "Optional title attribute"
