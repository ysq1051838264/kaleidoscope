### 基本操作
```
与（&）
或（|）
非（~）
异或（^）
左移（<<）
无符号右移位（>>>）
带符号右移（>>）
```

### 获得最右侧（低位）的 1
```
n & (~n + 1)
```

### 移除最右侧（低位）的 1
```
n & (n - 1)
```
或
```
n - n & (~n + 1)
```

### 求二进制数中1的个数
```
求二进制数中1的个数 (上)
http://blog.chinaunix.net/uid-20729605-id-1884367.html
求二进制数中1的个数 (下)
http://blog.chinaunix.net/uid-20729605-id-1884368.html
MIT HAKMEM算法分析
https://blog.csdn.net/msquare/article/details/4536388
```
