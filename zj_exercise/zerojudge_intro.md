zerojudge_intro
===
###### tags: `colde_garage_python_2019`
![](https://i.imgur.com/ws2GyW1.png)
# How to start your first code on zerojudge
## the "hello world problem"
https://zerojudge.tw/ShowProblem?problemid=a001
### example code
```python
import sys
for s in sys.stdin:
    print('hello, '+s)
```
## a042: 平面圓形切割
https://zerojudge.tw/ShowProblem?problemid=a042
### example code
```python
import sys
for s in sys.stdin:
    num = int(s)
    print(num**2 - num + 2)
```
# try it yourself ^ ^
保證十行內可以解完  
基礎題  
https://zerojudge.tw/ShowProblem?problemid=a044  
https://zerojudge.tw/ShowProblem?problemid=a111  
## a111 template
```python
import sys
for s in sys.stdin:
    # trun s to int
    if s == 0:
        break
    # print answer
```
挑戰題 9/30更新題示 (已更新在下方 ^ ^)  

??? 就是你要完成的部分  
其實這題只要 4 行就能搞定  
簡單八
```python
import sys
for s in sys.stdin:
    ???
    print("%g" % ???)
```
https://zerojudge.tw/ShowProblem?problemid=b757  



