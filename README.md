重新开发的poc检测工具，非开源。

利用goja动态生成变量。

利用govaluate检测响应是否满足表达式。

兼具一定的动态性，以及go的高并发性。

`-h`查看帮助信息。

测试逻辑发包规则
```
goscan.exe -taregt http://www.baidu.com -r rules\test.yaml
```

对单个目标批量执行struts2检测
```
goscan.exe -taregt http://localhost:8080/S2-015/welcome.action -r rules\struts2\
```

等有时间补上使用说明。
