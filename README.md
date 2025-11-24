
# <p align="center">Campus Canteen Ordering System</p>

基于 MySQL+Django 实现**校园食堂点餐系统**。

主要环境：

- PowerDesigner
- MySQL Workbench 8.0 CE
- Python 3.8
- Django 3.2.8
- BootStrap 3.3.7
- Django-simpleui

## 系统功能 :snake:

<div align="center">
	<img src="img/func1.png" alt="管理员模块" align="center" width=80% />
	<img src="img/func2.png" alt="用户模块" align="center" width=80% />
</div>

## 项目结构 :pencil:

```
django_CCOS
 ├── canteen				//app1
 ├── customer				//app2
 ├── dish				//app3
 │   ├── admin.py
 │   ├── apps.py
 │   ├── migrations
 │   ├── models.py			//数据库模型
 │   ├── tests.py
 │   ├── urls.py
 │   ├── views.py			//实现的视图
 │   └── __init__.py
 ├── django_CCOS
 │   ├── asgi.py
 │   ├── settings.py			//配置文件
 │   ├── urls.py
 │   ├── wsgi.py
 │   └── __init__.py
 ├── manage.py
 ├── media				//图片文件
 │   └── images
 ├── static				//样式文件
 │   ├── bootstrap-3.3.7-dist
 │   ├── css
 │   └── js
 └── templates				//页面模板 
     ├── base.html
     ├── canteen
     │   ├── canteen_base.html
     │   ├── canteen_list.html		//食堂展示
     │   └── shop_list.html		//窗口展示
     ├── customer
     │   ├── index.html
     │   ├── information.html		//完善用户信息
     │   ├── login.html			//登录界面
     │   ├── logout.html		//登出界面
     │   ├── register.html		//注册界面
     │   └── show_info.html		//个人
     └── dish
         ├── dish_base.html
         ├── dish_list.html		//菜品展示
         └── my_order.html		//我的订单
```


