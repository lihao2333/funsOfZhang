## awk
Q: 传入shell变量
A:
```
for i in `seq 5`;do
echo |awk -va=$i '{print a," 123"}'
done

```
output:
```
1  123
2  123
3  123
4  123
5  123
```
Q:获取字符"RL"之后的东西
A:`awk -F 'RL' '{pritn $NF}'` 
