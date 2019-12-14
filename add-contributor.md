---
url: add-contributor
public: 1
---

# 贡献者管理

**使用Github issue**

在Github issue中新建并按下列格式评论：

```
@all-contributors please add <username> for <contributions>
```

**使用命令**

参考[文档](https://yarn.bootcss.com/docs/install/)安装yarn，然后添加：

```
# Add new contributor <username>, who made a contribution of type <contribution>
yarn contributors:add add <username> <contribution>
# Example:
yarn contributors:add add jfmengels code,doc
```