这是一个简单的，轻量级的 php 开发框架，采用 MVC 开发模式。

数据库访问采用 PDO，可以配置多个主从分离的 MySQL 数据库

模板引擎 Smarty，也可以采用原生的 php 内嵌方式

调用的方式为：
http://www.domain.com/index/index

index 为默认的模块名和方法名，可以省略

第一个 index 为模块 module 第二个 index 为动作 action

框架目录结构：
xf\_php

|-- application
> |-- cache
> |-- config
> > |-- config.php

> |-- controller
> > |-- IndexController.php

> |-- view
> > |-- index
> > |-- index.html

> |-- viewc
|-- libraray
> |-- smarty
> |-- session.php
|-- www
> |-- css
> |-- js
> |-- index.php
|-- xfphp
> |-- XF\_Application.php
> |-- XF\_Cache.php
> |-- XF\_Controller.php
> |-- XF\_Database.php
> |-- XF\_Exception.php
> |-- XF\_Factory.php
> |-- XF\_Http.php
> |-- XF\_Page.php
> |-- XF\_Request.php
> |-- XF\_Response.php
> |-- XF\_Router.php
> |-- XF\_Util.php

－－－－－末完待续