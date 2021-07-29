# Contribute specification


## git usage

> commit

```shell
# 功能
git commit -m "feat(web): mssage"
# 修复
git commit -m "fix(web): mssage"
# 文档
git commit -m "doc(web): mssage"
# 重构
git commit -m "refactor(web): message"
```

> branch
```shell
# 功能
git checkout -b feat/[feature_name]
# 修复
git checkout -b fix/[fix_point_name]
# 文档
git checkout -b doc/[doc_name]
# 重构
git checkout -b refactor/[module_name]
```
> submodule

```shell
git submodules add [repo_url] [dirname]
git submodules rm [dirname]  
```