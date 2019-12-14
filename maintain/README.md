---
url: maintain-readme
public: 1
---

本仓库是通过 GitHub 维护并通过[瓦雀](https://github.com/yesmeck/waque)发布到[语雀](https://www.yuque.com/shixiangwang/gucm2q)上的。

在新的机器上请先配置，如果已配置好请查看维护内容。

## 配置


```
$ npm i -g waque
```

> 安装要学会变通。

从语雀<https://www.yuque.com/settings/tokens>中获取 token 并存储为 YUQUE_TOKEN 环境变量方便后续使用。


## 维护

增加和修改内容后使用 git 进行 commit，然后上传文档。

```
$ waque upload -t $YUQUE_TOKEN
```

上面的命令会自动上传文档。下面命令指定上传`foo.md`和`bar.md`到语雀。

```
$ waque upload foo.md bar.md -t $YUQUE_TOKEN
```

如果存在瓦雀使用问题请到官方仓库<https://github.com/yesmeck/waque>报告。