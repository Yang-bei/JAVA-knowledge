
1异常捕获处理，自己处理了异常，没有抛出，解决：手动抛出

2抛出检查异常，配置rollbackFor属性为Exception

3非public方法导致的事务失效，改为public