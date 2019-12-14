---
url: add-contributor
public: 1
---

# 贡献者管理

**使用 Github issue**

在 Github issue 中新建并按下列格式评论：

```
@all-contributors please add <username> for <contributions>
```

`<username>` 替换为 GitHub handle，如 `@ShixiangWang`。
`<contributions>` 替换为贡献类型，以 `and` 分隔，[点击阅读合法名字](https://allcontributors.org/docs/en/emoji-key)。
一个例子参考[这里](https://github.com/XSLiuLab/XSLab-docs/issues/2#issuecomment-565725526)。

**使用命令**

参考[文档](https://yarn.bootcss.com/docs/install/)安装yarn，然后添加：

```
# Add new contributor <username>, who made a contribution of type <contribution>
yarn contributors:add add <username> <contribution>
# Example:
yarn contributors:add add jfmengels code,doc
```