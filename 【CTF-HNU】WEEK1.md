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
![Pasted image 20250311173812](https://github.com/user-attachments/assets/e6fecd90-be72-4da7-b382-13dbf6b3499b)

##  get_post

使用Hackbar，load一下，输入?a=1![Pasted image 20250311180941](https://github.com/user-attachments/assets/95fd4eb5-bf80-441c-ba94-349db362ff5b)

使用POST方法，直接输入b=2![Pasted image 20250311181624](https://github.com/user-attachments/assets/b0ba3d88-aa2f-4dfc-857c-6fde0217d99d)

## robots协议
[[【CTF-知识】robots协议]]
看完了robots协议，知道这是一个限制爬虫的东西，也就是说要进行目录信息收集，直接使用dirsearch进行一个目录扫描。![Pasted image 20250313090039](https://github.com/user-attachments/assets/1050b94d-b041-4aa4-ba86-37c931dc7d45)

发现有一个/robots.txt文件，在网页进行访问,拿到flag位置![Pasted image 20250313090213](https://github.com/user-attachments/assets/4ba7c263-687a-4ff4-869e-594ca587ab74)



