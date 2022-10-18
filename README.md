
ClusterCloudManagerPlatformCore 是KubeVela V1.5.2版本，目前已经与其他产品
进行了业务上的耦合，业务场景已经做了。
在KubeVela V1.5.2版本上做了响应的处理：

1.所有接口都取消了ws.Filter(authCheckFilter)

2.cluster API 增加了ListClusterNamespace接口和功能

3.所有接口涉及到userName都改成了admin用户

4.project中取消了 项目中默认带交付目标

5.增加了chart文件上传，harbor等信息的configmap存储等功能
6、增加了查询集群主机，和给主机增删改查标签功能

将该版本作为main版本，其他开发的项目进行拉分支处理。

