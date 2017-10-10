## hello程序 (2017.10.10)
1. 
```
我们也可以将代码修改为如下形式来执行脚本（在开头添加：#!/usr/local/bin/lua）：
#!/usr/local/bin/lua

print("Hello World！")
```
2. 
```
1)以上代码中，我们指定了 Lua 的解释器 /usr/local/bin directory。
2)加上 # 号标记解释器会忽略它。接下来我们为脚本添加可执行权限，并执行：
./test.lua 
Hello World！
```