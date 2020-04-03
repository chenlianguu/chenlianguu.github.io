---
title: Kubernetes集群部署-admin
top: false
toc: true
mathjax: true
date: 2020-01-09 12:32:11
index_img: https://www.ovh.com/blog/wp-content/uploads/2019/01/kubernetesblog02.jpg
summary:
tags:
 - kubernetes
 - 部署
categories:  kubernetes
---

k8s的搭建主要有三种方式：kubeadmin安装、docker安装及二进制安装，其中二进制安装方式最为复杂需要部署人员了解网络https，ca证书等方面的知识，kubeadmin安装方式大大简化了部署操作，但是对K8s的HA支持处于测试阶段，刚入门建议尝试kubeadmin方式安装。docker安装我并不觉得合适，本身k8s作为容器编排系统部署在docker里面，网络及相关端口配置较为复杂，为了避免埋下太多的坑，本人没有尝试这种方式进行安装。

具体安装部署我就不写在这里了，分享一套自己看的k8s入门视频，很简短能够快速了解k8s，当时k8s学习曲线是比较陡峭的。

👉🏻[百度云盘](https://pan.baidu.com/s/1ieZmpZdsae73PacD9FZDYA) 密码:amlo

👉🏻[安装部署文档](https://alevelhome-my.sharepoint.com/:w:/p/chenliang/EbQBPVmKj7VBpKZGYo02h4YBGbutlFV-28jq86GsR76HzQ?e=SgE4o5)  

按照此文档部署基本没啥坑，注意的是部分镜像在国外服务器，需要替换成文档作者国内的镜像即可。

------
最近看到新的工具rancher，企业级管理运维kubernetes集群的好工具的。后续继续更新