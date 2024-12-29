# DockerAPITool
DockerRemoteAPI未授权访问(2375端口)利用工具，支持容器逃逸

**造轮子的原因**：内网经常遇到DockerApi未授权访问漏洞，每次都需要使用docker连接进行后续操作，赛博马喽比较懒，于是就有了这个工具。。。



**用法**：

1、输入ip:port点击按钮即可获取docker环境信息、镜像、容器列表。
<img width="1100" alt="image" src="https://github.com/user-attachments/assets/9138f8be-376c-4669-b856-c40afcf46785" />



2、镜像列表右键可以用此镜像模版创建容器，默认特权模式，填写容器名（不能重复），需要挂载宿主机的目录和挂载到容器内的目录位置（建议都默认）。创建完点击获取信息就能刷新看到了。

<img width="600" alt="image" src="https://github.com/user-attachments/assets/a34674fa-8cd9-4136-8dd2-1c5b8c129d2d" />


3、容器列表右键可以执行容器内命令、删除容器（慎用）、容器逃逸。容器逃逸就节省了开虚拟机手动敲命令的时间，内置的Exp暂时仅在ubuntu靶场实验通过，必须得用默认配置创建容器才行；centos懒得搭，应该是没啥问题。。。
<img width="1089" alt="image" src="https://github.com/user-attachments/assets/9ea945bf-3954-48d9-9eb3-4b2c83a50f04" />

<img width="600" alt="image" src="https://github.com/user-attachments/assets/e3cb9944-6b85-4e98-962d-8961b69a27be" />


具体的请看VCR：


https://github.com/user-attachments/assets/e4e13856-15de-4d57-8efa-f2c076842f1d



**网络安全工具使用免责声明**

本工具所有演示环境均在本地搭建。
本工具仅供合法、安全的网络安全自查使用。用户不得利用本工具进行任何非法活动，包括但不限于未经授权的入侵、攻击或数据窃取。开发者不对任何违法使用本工具的行为负责，用户应承担所有因非法使用工具所产生的法律责任。
开发者不对因使用本工具造成的任何损害或损失负责，用户承诺仅在合法授权的网络环境中使用本工具。
