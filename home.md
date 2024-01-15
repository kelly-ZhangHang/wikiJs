---
title: IPSecVPN配置参数
description: 
published: true
date: 2024-01-15T07:09:14.015Z
tags: ipsecvpn
editor: markdown
dateCreated: 2024-01-15T07:05:39.883Z
---

# IPSecVPN
武汉联通IP	220.249.121.13	武汉保护网段	10.17.64.0/21
武汉电信IP	58.48.78.126	
SA协商时间	28800s,3600s	IKE	AES-128-SHA2-256-DH14
PFS DH组	24	IPSec	AES-128-SHA2-256
DPD间隔	10s	DPD重传	5s

北京联通IP	124.65.15.38	北京保护网段	"10.17.8.0/22
10.17.34.0/24"
北京电信IP	106.39.2.167	共享秘钥	cmicvpn
SA协商时间	28800s,3600s	IKE	AES-128-SHA2-256-DH14
PFS DH组	24	IPSec	AES-128-SHA2-256
DPD间隔	10s	DPD重传	5s
			