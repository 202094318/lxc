# LXC

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FspiritLHLS%2Flxc&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

## 一键母鸡开小鸡

## 更新

2023.07.24

- ubuntu20无法被检索到，上次更新替换了image的查找方式使用json解析，结果判断出问题了，之前没用jq解析json的时候没这个问题的，已修复
- 开设alpine的时候我搬运的我之前写docker虚拟化开设alpine的时候的脚本设置ssh，没想到配置文件不一样，已修复
- 修复了centos系上部分系统ssh开设的问题，对cloudinit文件进行覆盖修改

[更新日志](CHANGELOG.md)

## 待解决的问题

- 部分机器的ubuntu22系统lxd开出的容器没网，待修复，此时建议回退ubuntu20
- 开设的容器不支持centos7，centos8，仅支持centos的stream版本，待添加支持([参考](https://github.com/spiritLHLS/lxc/issues/20#issue-1816499383))
- 使得母鸡支持更多的系统版本

## 说明文档

[virt.spiritlhl.net](https://virt.spiritlhl.net/) 中 LXD 分区内容

## 友链

VPS融合怪测评脚本

https://github.com/spiritLHLS/ecs

朋友写的针对合租服务器使用的(需要有一定的LXD或LXC基础，否则你看不懂部分设置)(更新可能有点缓慢)

https://github.com/MXCCO/lxdpro

## Stargazers over time

[![Stargazers over time](https://starchart.cc/spiritLHLS/lxc.svg)](https://starchart.cc/spiritLHLS/lxc)
