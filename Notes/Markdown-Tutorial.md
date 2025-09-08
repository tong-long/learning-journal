# markdown语法
## 1、标题(Headers)
**使用 # 的数量来表示标题的级别，从1级（最大）到6级（最小）。**
```markdown
# 这是一级标题 (H1)
## 这是二级标题 (H2)
### 这是三级标题 (H3)
#### 这是四级标题 (H4)
```
效果：
# 这是一级标题 (H1)
## 这是二级标题 (H2)
### 这是三级标题 (H3)
#### 这是四级标题 (H4)  

## 2、段落和换行 (Paragraphs & Line Breaks)
- 段落：用一个空行来分隔两个段落。
- 换行：在一行的结尾输入两个空格再按回车，或者直接输入一个空行。  

## 3、强调 (Emphasis)
```markdown
*这是斜体文本* 或者 _这也是斜体文本_
**这是粗体文本** 或者 __这也是粗体文本__
***这是粗斜体文本*** 或者 ___这也是粗斜体文本___
```
效果：  
*这是斜体文本* 或者 _这也是斜体文本_  
**这是粗体文本** 或者 __这也是粗体文本__  
***这是粗斜体文本*** 或者 ___这也是粗斜体文本___  

## 4、列表 (Lists)
- 无序列表：使用 -, *, 或 +
```markdown
- 项目一
- 项目二
  - 子项目二（缩进两个或四个空格）
* 项目三
```
效果：  
- 项目一
- 项目二
  - 子项目二（缩进两个或四个空格）
* 项目三

## 5、链接和图片 (Links & Images)
- 链接：[链接文本](URL "悬停提示文字（可选）")
```markdown
访问 [Google](https://www.google.com) 搜索。
访问 [GitHub](https://www.github.com "一个代码托管平台") 看看。
```
效果：  
访问 [Google](https://www.google.com) 搜索。  
访问 [GitHub](https://www.github.com "一个代码托管平台") 看看。  
- 图片：![图片替代文本](图片URL "悬停提示文字（可选）")
```markdown
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png "GitHub Logo")
```
效果：  
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png "GitHub Logo")
> 注意：图片语法前多个一个 !。替代文本在图片无法加载时显示，对无障碍访问很重要。

## 6、代码 (Code)
- 行内代码：用一个反引号 ` 包裹  
```markdown
使用 `print("Hello, World!")` 函数来打印。
```
效果：  
使用 `print("Hello, World!")` 函数来打印。  
- 代码块：用三个反引号 ``` 包裹，并可在开头指定语言以实现语法高亮
````markdown
```python  
def hello_world():
    print("Hello, World!") # 这是Python代码

hello_world()
```
````
效果：  
```python  
def hello_world():
    print("Hello, World!") # 这是Python代码

hello_world()
```
>如果你在这里试图浮现这篇教程，你可能会出限一个问题：
>>“上面的代码块我无法使其在文档中完整显现三个反引号”

>这是一个**“转义”**问题  
>**解决方案：使用更多反引号包裹  
>规则是： 如果你想在代码块里显示“三个反引号”，你就必须用“四个反引号”来包裹整个代码块。** 
 

## 7、引用 (Blockquotes)
使用 > 符号。
```markdown
> 这是一个引用。
> 这是引用的第二行。
>
> > 这是嵌套的引用。
```
效果：  
> 这是一个引用。
> 这是引用的第二行。
>
> > 这是嵌套的引用。
## 8、分割线 (Horizontal Rules)
使用三个或更多的 ---, ***, 或 ___。  
```markdown
---
___
***
```
效果：  
---
___
***

> 今日学习：Git克隆操作。
