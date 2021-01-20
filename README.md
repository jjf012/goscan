# 中文

一个可配置化发送请求的POC框架。利用goja动态生成变量，利用govaluate检测响应是否满足表达式。

使得该工具一定的可配置性，结合go语言的高并发特性，实现高速检测。

使用`-h`查看帮助信息

测试逻辑发包规则
```
goscan.exe -taregt http://www.baidu.com -r rules\test.yaml
```

对单个目标批量执行struts2检测
```
goscan.exe -taregt http://localhost:8080/S2-015/welcome.action -r rules\struts2\
```

等有时间补上使用说明。

# English

Use goja to dynamically generate variables, and use govaluate to detect whether the response satisfies the expression.

Use the certain configurability of this tool, combined with the high concurrency of go language, to achieve high-speed detection.

Use `-h` to view help information

Test logic contracting rules
```
goscan.exe -taregt http://www.baidu.com -r rules\test.yaml
```

Perform struts2 detection on a single target in batches
```
goscan.exe -taregt http://localhost:8080/S2-015/welcome.action -r rules\struts2\
```

Wait for time to fill in the instructions.
