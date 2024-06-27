# c00147-ssm-studentscore
基于SSM（非maven）的学生成绩管理系统-有报告

## 项目简介

这是一个基于SSM（非maven）学生成绩管理系统主要可实现三种用户的登录效果，其中包括管理员、教师和学生。管理员可以在本系统中对学生信息、教师信息、课程信息、公告信息进行管理，也可以对所有学生的成绩进行查看，可以操作本系统的菜单权限；教师登录系统可以查看公告、我的课程以及学生成绩的列表；学生登录系统也可以查看对应的公告、选课以及退课和查看自己的课程成绩等功能。


## 项目获取
> [源码获取地址](http://www.manoncode.cn/details?id=147)

 
## 开发环境

运行环境：推荐jdk1.8；
开发工具：eclipse以及idea（推荐）、vscode、redis、node环境（16.X）；
操作系统：windows 10 8G内存以上（其他windows以及macOS支持，但不推荐）；
浏览器：Firefox(推荐)、Google Chrome(推荐)、Edge;
数据库：MySQL8.0(推荐)及其他版本（支持，但容易异常尤其MySQL5.7（不含）以下版本）；
数据库可视化工具：Navicat Premium 15（推荐）以及其他Navicat版本
是否maven项目：否

>登录：
管理员：用户名：admin 密码：admin 
教师：用户名：1560310 密码：1560310
学生：用户名：15603102221 密码：15603102221
>
>注意：运行项目应用名改为/
修改应用名教程：https://mp.weixin.qq.com/s/NItqOfcfUCsWxkpDFS17SQ

## 项目技术
 
后端：Spring、SpringMVC、Mybatis、mysql
前端：jsp、layui、jquery、ajax

## 运行截图



1.项目结构 
![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/7667ccc74fff4c119d6e5cc17f1f8ae4.png#pic_center)


  2.数据库模型 

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/61c81686fd0b4fee9991fc6aa0b4146c.png#pic_center)





  登录页面 

![登录页面](https://img-blog.csdnimg.cn/img_convert/f503359b34ca57f05344b5469cc7d403.png)

  管理员-成绩报表 

![管理员-成绩报表](https://img-blog.csdnimg.cn/img_convert/aefcd8d93c191bc2c142efedf3dddbe0.png)

  管理员-公告管理 

![管理员-公告管理](https://img-blog.csdnimg.cn/img_convert/eb8dae93c82a602a74bd755e99115d6a.png)

  管理员-教师信息管理 

![管理员-教师信息管理](https://img-blog.csdnimg.cn/img_convert/fb9e38ca2d703714b35383caa7bd84c0.png)

  管理员-课程信息管理 

![管理员-课程信息管理](https://img-blog.csdnimg.cn/img_convert/1987e252fd0ad264846e65ff438674fa.png)

  管理员-系统管理 

![管理员-系统管理](https://img-blog.csdnimg.cn/img_convert/af272db1e20b5e31792de19061ff9f9e.png)

  管理员-学生信息管理 

![管理员-学生信息管理](https://img-blog.csdnimg.cn/img_convert/5a6c52e31fae98c809271702697bf78a.png)

  教师-公告查看 

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/4214fe6b3056454d8f133a7826d3c846.png#pic_center)


  教师-我的课程 
![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/80c79ad4e78b463a8f0cf54d2c9bca54.png#pic_center)



  教师-学生成绩列表 

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/d4b0d72ccb534ef28684a33146f700c2.png#pic_center)


  实验报告 

![实验报告](https://img-blog.csdnimg.cn/img_convert/41a93847d925ddd32dcdcac2b6a09618.png)

  下载所得 

![下载所得](https://img-blog.csdnimg.cn/img_convert/efb8226875fe50aa6279a62a371d740b.png)

  修改密码 

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/cce36e1a1a4b499ea3b2e2737e342659.png#pic_center)


  学生-公告查看 

![学生-公告查看](https://img-blog.csdnimg.cn/img_convert/d1566ccb913c72d85daa5b663ce37aaf.png)

  学生-我的成绩 

![学生-我的成绩](https://img-blog.csdnimg.cn/img_convert/35ba765133c76c959c246f712df75535.png)

  学生-选课及我的课程 

![学生-选课及我的课程](https://img-blog.csdnimg.cn/img_convert/e4c78dc878b789396168173524e3bb5c.png)
