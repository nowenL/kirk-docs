## 应用 {docsify-ignore}
一个应用可以包含多个服务，实现应用微服务化。

## 服务 {docsify-ignore}
Kubernetes的Service概念，一个服务基于一个镜像创建，可以包含多个容器实例，实现弹性伸缩。

## 容器 {docsify-ignore}
Container，容器实例由镜像生成。

## 镜像 {docsify-ignore}
Kubernetes的Image概念，容器应用打包的标准格式，除了包含应用代码，还包含应用运行所需的库、资源、配置等文件，集中存储在镜像仓库中。

## 公有镜像 {docsify-ignore}
所有七牛容器云注册用户都可以访问拉取的应用镜像。

## 私有镜像 {docsify-ignore}
只有具备相关访问权限的用户才能拉取的应用镜像，一个组织下的成员可以同时访问。

## 空间 {docsify-ignore}
Kubernetes的Namespace概念，空间之间存在资源隔离，进程相互独立。

## 集群 {docsify-ignore}
为容器运行提供依赖的云资源，由若干个主机节点组成。
