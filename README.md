# 咕泡学院

通常又叫模板方法模式。

需要有些抽象方法，需要在子类里实现。

利用模板模式，自己写一个 JdbcTemplate 

模板方法的定制，不仅可以通过定制abstract方法，也可以通过定制模板方法入口参数类型来改变该模板方法实现。

美洲人、亚洲人（模板类，共性的，满足开闭原则：模板类修改关闭，子类继承开放）。 

![img](http://note.youdao.com/yws/res/29447/WEBRESOURCE070eccf41ff391a8422ce4ff3903787e) 

不要把世界所有的人的基类都挂在相同的基类下，否则这样的基类会越来越复杂，可以把人安装某些共性细分子类。
