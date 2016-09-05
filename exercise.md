# 作业

1. **找一个**客户端连接数据库服务器   
 - 数据库地址：52.8.67.180，端口 3306  
 - 数据库用户名和密码：dec2013stu  和   dec2013stu 

3. 链接数据库服务器之后，每位同学建立自己的数据库、数据表；借助1中的客户端手动录入若干条数据。  
  - **数据库只能用 stu_num  命名。其中num是各自学号。使用其他方法无法无法创建。**  

  - **不允许出现两位同学相同数据库和表的情况**  

3. 按照课堂上的思路，写一个dart程序连接服务器，读取数据，将数据转换为json格式
4. 承接上一次课，通过web 服务器的方式将上述json数据提供给你的客户端应用
5. 承接dart动态控制html的技术，将上述从服务器获得的json数据在页面上展现出来  
6. 各小组clone 各组对应的project。在上面建立dart应用，写出各自index.html框架来。  
  - 在项目中新建一个doc文件夹
  - doc文件夹中新建一个.md文件。
  - .md文件中录入如下： 
  
| 控件id |  描述|
| -- |  -- |
| nameFile | 姓名输入框|
| classFile | 班级输入框|
| ... | ...|
| 以此类推 | 以此类推|
md 文件中使用如下方法编写上述表格：
```
| 控件id |  描述|
| -- |  -- |
| nameFile | 姓名输入框|
| classFile | 班级输入框|
| ... | ...|
| 以此类推 | 以此类推|
```
  - md文件内容就是一个id字典，供小组团队合作时候，方便dart编程中选择器调用 
  - 
  ```dart
querySelector（#id）;
```



作业评价标准  
1. 个人完成度（基准分75）   
 - 不是用自己的数据库 -5分
 - 没有构造出完整的程序结构 -5分
 - 仅限课堂上的那点代码，没有新进展 -5分
 - **疑似抄袭同学代码 -25分**
 - 根据代码和成果情况上下浮动 5分
 - 超额完成 + >15
    - 所谓超额完成，包括但不限于：  
      - 建立了复杂的数据库表
      - html页面复杂度超越课堂案例基本要求
      - 应用css复杂度超越课堂案例基本要求
      - ...
2. 本次小组完成度（小组成果只有一次打分，不是按照每次打分。最终基准分80分）
 - 没有clone各组项目，并基于该项目建立新的dart项目 -1分
 - 没有开始建立html主文件 -1分
 - 没有建立对应的.md文件及设计主文件html元素id -1分  
 **强调：到最后并不是小组成员分数一样，可以通过git做统计工作内容，依然会有差别**