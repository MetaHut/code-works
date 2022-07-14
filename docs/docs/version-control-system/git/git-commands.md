---
sidebar_position: 2
---

# Commands

Git Commands

## tag

* 删除本地某个tag

```shell
git tag -d tag-name
```

* 删除本地全部tag

```shell
git tag -d $(git tag -l)
```

* 删除本地全部tag

```shell
git push origin :refs/tags/tag-name
```
