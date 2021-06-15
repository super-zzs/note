# git的使用

## 版本控制

实质：git管理文件夹



## 步骤

- 进入要管理的文件夹
- 初始化

```
git init
初始化文件夹
```



- 查看/检测当前目录下的文件状态

``` 
git status
- 红色：新增的 / 修改了原来的老文件
- 绿色：git已经管理起来的文件
- 生产版本
```



- 管理制定文件，将文件添加到当前目录git的版本控制（红变绿）

```
git add  文件名
git .
```



- 提交并生成版本信息

```
git commit -m '描述信息'   
```



- 查看版本信息

```
git log  
```



- 个人信息配置：用户名以及邮箱

```
- git config --global user.name '用户名'
- git config --global user.email '邮箱'
假如没有配置，在commit时候会报错
```







