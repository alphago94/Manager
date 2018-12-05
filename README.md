# Manager
后台管理系统v1.0

信息管理系统

技术需求
	servlet+jsp+mvc+jdbc
	
软件需求
	开发工具 Eclipse
	数据库 mysql
	服务器 Tomcat
	浏览器 Chrome
	
硬件需求
	一台电脑

功能需求
	用户登录
	用户注册
	用户退出
	查看个人信息
	修改密码
	查询所有用户信息

数据库设计
	用户表 t_user
	表设计
	
	字段名		类型		约束
	uid			int(10) 	主键,非空,自增
	uname		varchar(50)	非空
	pwd			varchar(50)	非空
	sex			char(2)		非空
	age			int(3)	
	birth		date
	
代码规范
	命名规范
		包名 com.alphago94.*
		类名 首字母大写, 见名知意
		变量名和方法名 驼峰原则 见名知意
	注释规范
		方法功能注释
		方法体核心位置必须有说明注释
	日志规范
		使用log4j进行日志输出(可选)
		数据流转的位置必须有后台输出语句

功能设计
	用户登录
		创建登录页面(直接用模板), html文件复制到jsp
