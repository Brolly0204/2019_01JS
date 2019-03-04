# git

## 老师和学生

老师仓库地址：https://github.com/Lwenli1224/2019_01JS.git

### 拉取讲义

#### 第一种方式

直接将老师远程仓库 clone到直接本地

```
git clone https://github.com/Lwenli1224/2019_01JS.git
```
以后更新

```
git pull origin master
```

#### 第二种

先fork一份老师的仓库 到 自己的GitHub里

然后再将fork的仓库 从你的GitHub里 clone下来

```
git clone <你fork后的仓库地址>
```

让你的本地和老师建立联系
```
git remote add teacher https://github.com/Lwenli1224/2019_01JS.git
```

以后当老师更新时

```
# 拉取老师的更新
git pull teacher master

# 从你的本地推送到 你的远程

git push origin master
```


