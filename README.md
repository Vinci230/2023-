# 2023-蓝山寒假考核脚本

本项目目标是利用python+GitHub actions实现对学员假期考核的追踪  

## 用法

1. 新建一个仓库
2. 使用git submodule 添加学员的仓库
3. 配置actions的workflow，定时执行
4. workflow将会获取当天内学员的commit内容，并且附加到readme的顶部

## workflow例子

```yaml
some example
```

## 目录结构


"Commit ID: 69a5571015029b7c3729eb362d67a0e193d1b43a
Author: Vinci230 <lienxithy@gmail.com>
Date: Sat Jan 27 23:21:50 2024 +0800
Message: clone仓库成功且测试只差看一天内的记录成功

"
"Commit ID: 381e993b340a0fd359dca40aa1c2fd23f7c64044
Author: Vinci230 <lienxithy@gmail.com>
Date: Sat Jan 27 23:19:37 2024 +0800
Message: 测试之查看27号这天的commit信息成功，但貌似未完全clone仓库？

"
"Commit ID: bd7103917e74cff06a5ff16d8ffc6d1a3bafe786
Author: Vinci230 <lienxithy@gmail.com>
Date: Sat Jan 27 23:14:51 2024 +0800
Message: 文件换位

"
"Commit ID: d73d026595fd7543c473d86d76d29ec23faef79c
Author: Vinci230 <lienxithy@gmail.com>
Date: Sat Jan 27 23:13:15 2024 +0800
Message: Merge remote-tracking branch 'origin/main'

"
"Commit ID: 35ca1779e9a97af8c77b428e184243f212ab4e8d
Author: Vinci230 <lienxithy@gmail.com>
Date: Sat Jan 27 23:12:49 2024 +0800
Message: 文件换位

"
"Commit ID: 14ec1975590ea37ffcb219d4b560c4633ca482fe
Author: Vinci230 <lienxithy@gmail.com>
Date: Sat Jan 27 23:12:48 2024 +0800
Message: 文件换位

"
"Commit ID: 31513bc28930a1aedbea339dfeef56cbd3c0d40b
Author: Vinci230 <lienxithy@gmail.com>
Date: Sat Jan 27 23:10:14 2024 +0800
Message: 测试只24号信息并正确的打印出中文字符成功

"
"Commit ID: 820c7125e32e7ccefbdf9c0f6a8184ab33692d42
Author: Vinci230 <lienxithy@gmail.com>
Date: Sat Jan 27 22:13:44 2024 +0800
Message: 测试只查看每天提交

"
"Commit ID: 5940bba55923930142d884f57cf20cea8d1b7835
Author: Vinci230 <lienxithy@gmail.com>
Date: Sat Jan 27 20:30:59 2024 +0800
Message: clone 并print关于commit的信息

"