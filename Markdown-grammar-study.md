
[Markdown 官方教程参考链接](https://markdown.com.cn/extended-syntax/tables.html)
# 1  文字编辑不部分
## 1.1 标题 “#”
标题前#号加空格
## 1.2 分隔线 “***”
三个星手动添加分隔线
示例：
***
## 1.3 文字加粗“** **”
示例：加粗最后两个**文字**
## 1.4 代码块引用
### 1.4.1 部分内容引用 “` ``”
示例:  
I can't connect my ``critical assets`` to the network because they would be exposed to attacks
### 1.4.2 独立代码块 "``` ```"
```
const isWeekday = (date) => date.getDay() % 6 !== 0;
console.log(isWeekday(new Date(2021, 0, 11)));
console.log(isWeekday(new Date(2021, 0, 10)));
```
### 1.4.3 代码块编程语言上色
"```"后面备注编程语言，会高亮上色不同内容进行显示"
示例：
```javascript
const isWeekday = (date) => date.getDay() % 6 !== 0;
console.log(isWeekday(new Date(2021, 0, 11)));
console.log(isWeekday(new Date(2021, 0, 10)));
```
## 1.5 列表
### 1.5.1 有序列表 "数据+英文句号+空格"
示例:网络安全流程：
1. 识别
2. 防护 
3. 监测
4. 响应
5. 恢复
### 1.5.2 无序列表 “减号+空格+内容”
示例：网络安全流程
- 识别
- 防护
- 监测
- 响应
- 恢复

## 1.6链接
## 1.6.1 网址链接
[链接内容]+(链接地址)  
示例：  
[github个人主页](https://github.com/)
## 1.6.2 图片链接
### 1.6.2.1 不显示图片  
[图片自定义名称]+(图片地址)  
示例: 
[my-github-Profile picture](https://avatars.githubusercontent.com/u/127872034?s=400&u=3c7d102ff39b4ac8bcc5cd99e6a15d2c231c9d98&v=4)

### 1.6.2.2 显示预览
!+[图片自定义名称]+(图片地址)  
示例: 
![my-github-Profile picture](https://avatars.githubusercontent.com/u/127872034?s=400&u=3c7d102ff39b4ac8bcc5cd99e6a15d2c231c9d98&v=4)

## 1.7 表格
使用竖杠"|"和减号"-"来绘制表格
示例：  
|col1|col2|col3|
|-|-|-|
|black|white|yellow|
|blue|red|green|
