[返回上一级](../README.md) [返回首页](../../README.md)
# **Maven project**

## **文件介绍**
### **[dispatch.yml](./dispatch.yml)**
- 手动运行Workflows工作流程
### **[pr-check.yml](./pr-check.yml)**
- 用于 PR 的 CI 检查
### **[tagpush.yml](./tagpush.yml)**
- 用于版本发布使用

## **相关链接**
- **这里列出了使用的资源链接**

|名称|介绍|备注|
|:-:|:-:|:-:|
|[actions/checkout](https://github.com/actions/checkout)|用于拉取项目代码<br>从仓库中拉取项目代码||
|[actions/setup-java](https://github.com/actions/setup-java)|安装JAVA<br>用于安装指定的JAVA版本||
|[actions/upload-artifact](https://github.com/actions/upload-artifact)|上传构建<br>用于将构建好的项目上传||
|[ncipollo/release-action](https://github.com/ncipollo/release-action)|版本发布<br>将构建产物发布至Github Releases|仅在tagpush.yml使用|
|[hmarr/auto-approve-action](https://github.com/hmarr/auto-approve-action)|自动批准 GitHub 的 PR。|仅在dispatch.yml使用|