# CoolePHP
一个简单的PHP自动加载框架，持续更新中。。。

安装 composer require hahadu/coole-php dev-master

新建入口文件index.php

使用：引入'CoolePHP.php'文件;

include 'CoolePHP.php' 或者 include 'vendor/autoload.php';

新建文件夹
app\controller
打开app\controller目录
新建IndexController.php控制器文件

“<?php

namespace controller;

class IndexController{

	function index(){

		echo 'this is index function';

	}

	function demo(){

		echo 'this is demo function!';

	}

}

“
浏览器访问/index.php?m=index&a=demo
m 控制器名
a 方法名
