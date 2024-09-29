# Linux
Linux常用命令
## 查询root目录文件夹大小前10个
```
sudo du -h --max-depth=1 /root | sort -rh | head -n 10
```
### 制定python版本创建虚拟环境并激活
#### 创建
```
python3.12 -m venv envname #创建名为envname的虚拟环境
```
#### 激活
```
source envname/bin/activate #激活虚拟环境
```
####退出虚拟环境
```deactivate```
