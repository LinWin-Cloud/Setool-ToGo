# Setool ToGo
1. 发型于:2022.3.5
2. 作者:LinWInCloud

##### 本版本是Setool Master的特殊发行版本，同样会接受不定期的更新和修补
##### Setool ToGo是一个非常轻量化的精简版本，不过完全适用于及时、远程、隐蔽的社工测试
##### 源代码仓库不提供客户端终端用于远程社工，但是可以复制运行如下代码
##### 本项目的远程网络安全测试控制终端内置于Setool Main发型版本中
复制本代码到Linux终端内，修改{用户名}和{需要连接的IP}这些内容，填写的时候不包含{}符号，例如 ssh root@000.000.000.000 ...
###### 通过Gitee代码仓库内远程下载ZIP包（速度较快，无法获取更新）
ssh {用户名}@{需要连接的IP} mkdir remote && cd remote && wget https://gitee.com/LinWin-Cloud/packages.LinWinCloud.gitee/raw/master/Setool-ToGo/packages/Setool-ToGo.zip && unzip Setool-ToGo.zip && python3 setool.py
###### 通过Github远程仓库克隆（速度较慢，频繁不定期更新）
ssh {用户名}@{需要连接的IP} mkdir remote && cd remote && git clone https://github.com/LinWin-Cloud/Setool-ToGo.git && cd Setool-ToGo && python3 setool.py

# 更新日志
1. v1.0 2022.6.23 发布Setool ToGo 
2. v1.1 2022.6.24 更新源代码 
3. v1.2 2022.6.25 更新源代码、修复源码错误 
4. v1.3 2022.6.26 更新配置文件、修复文档错误 
5. v1.4 2022.6.27 更新配置文件 
6. v1.5 2022.6.28 修复原代码错误 
7. v1.6 2022.6.29 更新配置文件 
8. v1.7 2022.7.2 更新配置、说明、修复配置错误 
9. v1.8 2022.7.6 更新配置、源代码
10. v1.9 2022.7.10 更新源代码
11. v2.0 2022.7.28 修复源代码错误、更新源代码、更新配置
