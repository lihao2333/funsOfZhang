## perl
Q: 打印如下格式
```
111
222
333
```
A:`seq 3|perl -lne 'print "  ".$_ x 3'
