# ReTag
参考此Issue：[Breaking Change: .NET Docker Repo Name Change](https://github.com/dotnet/dotnet-docker/issues/2375)，由于名称变更导致的仓库移动，新的images应从https://hub.docker.com/_/microsoft-dotnet-sdk获取，但本仓库继续以dotnet-core存在并保持更新

-----

为解决`mcr.microsoft.com/dotnet/core/` 的 docker images `docker pull`过慢的问题而创建



本人在腾讯云中已公开`ccr.ccs.tencentyun.com/dotnet-core/`命名空间保存相关images

![](https://blog.wangshuai.app/img/tencenyun_aspnet_core_repository.png)

使用Azure Devops 每日更新 `latest` 镜像

