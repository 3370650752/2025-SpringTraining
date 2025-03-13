---
share: "true"
---


# 工具安装
- [x] **Hackerbar**：便于发送简单的请求和编码转化等等，强大的功能和简单的使用让它在ctf圈里很出名；
- [x] **BurpSuite**：抓包工具，同时也有爆破的功能；
- [x] **Dirsearch**：路径扫描工具，具体用处试试就知道了
- [x] **浏览器开发者工具**（浏览器自带的，不用下）：没得喷，这个是真神；

# 题目
## **view_source**

直接F12打开控制台，即可查看FLAG
![[Pasted image 20250311173812.png]]
##  get_post

使用Hackbar，load一下，输入?a=1![[Pasted image 20250311180941.png]]
使用POST方法，直接输入b=2![[Pasted image 20250311181624.png]]
## robots协议
[[【CTF-知识】robots协议]]
看完了robots协议，知道这是一个限制爬虫的东西，也就是说要进行目录信息收集，直接使用dirsearch进行一个目录扫描。![[
Pasted image 20250313090039.png]]
发现有一个/robots.txt文件，在网页进行访问,拿到flag位置![[Pasted image 20250313090213.png]]


