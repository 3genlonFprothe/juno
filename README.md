![logo](docs/logo.png)

# JUNO - A distributed application management system

[![Build Status](https://travis-ci.org/douyu/juno.svg?branch=master)](https://travis-ci.org/douyu/juno)
[![codecov](https://codecov.io/gh/douyu/juno/branch/master/graph/badge.svg)](https://codecov.io/gh/douyu/juno)
[![go.dev reference](https://img.shields.io/badge/go.dev-reference-007d9c?logo=go&logoColor=white&style=flat-square)](https://pkg.go.dev/github.com/douyu/juno?tab=doc)
[![Go Report Card](https://goreportcard.com/badge/github.com/douyu/juno)](https://goreportcard.com/report/github.com/douyu/juno)
![license](https://img.shields.io/badge/license-Apache--2.0-green.svg)<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-15-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

## Introduction

JUNO（朱诺） 是斗鱼数据服务组研发的分布式服务管理系统，核心功能为配置中心，能集中化管理应用不同环境、不同机房的配置；并且集成了监控中心、测试平台、日志中心等功能模块，采用Casbin进行规范化的权限管理，适用于微服务生命周期管理。

## Online Demo

[Jupiter Console (Juno)](https://jupiterconsole.douyu.com)

```
Username: admin
Password: admin
```

## Documentation

更多产品介绍参见 [Juno微服务治理系统介绍](http://jupiter.douyu.com/juno)

## Quick Start with Kubernetes

### Install Juno

- Github镜像源

```bash
kubectl apply -f https://github.com/douyu/juno/releases/download/latest/install.yml
```

- 阿里云镜像源（推荐国内使用）

```bash
kubectl apply -f https://hub.gitmirror.com/https://github.com/douyu/juno/releases/download/latest/install-mirror.yml
```

### Install Jupiter-Layout

- Github镜像源

```bash
kubectl apply -f https://github.com/douyu/jupiter-layout/releases/download/latest/install.yml
```

- 阿里云镜像源（推荐国内使用）

```bash
kubectl apply -f https://hub.gitmirror.com/https://github.com/douyu/jupiter-layout/releases/download/latest/install-mirror.yml
```

## Overview 
### [Monitor Dashboard]()
-----
Profile dashboard of app
[![monitorpyroscope](/docs/img/monitorpyroscope.png)](https://github.com/douyu/juno)
Overview metrics of app
[![monitoroverview](/docs/img/monitoroverview.png)](https://github.com/douyu/juno)
Instance metrics of app
[![monitorinstance](/docs/img/monitorinstance.png)](https://github.com/douyu/juno)
API metrics of app
[![monitorapi](/docs/img/monitorapi.png)](https://github.com/douyu/juno)
### [Pyroscope](https://github.com/pyroscope-io/pyroscope)
----
[![pyroscope](/docs/img/pyroscope.png)](https://github.com/douyu/juno)
### [Jaeger](https://github.com/jaegertracing/jaeger)
----
[![jaeger](/docs/img/jaeger.png)](https://github.com/douyu/juno)
## Bug and Feedback

For bug report, questions and discussions please submit GitHub Issues.

## Contribution

Please make sure to read the [CONTRIBUTING](CONTRIBUTING.md) before making a pull request.

Thanks for all the people who contributed to Juno！

## Contributors

<a href="https://github.com/douyu/juno/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=douyu/juno" />
</a>

## License

The project is licensed under the [Apache 2 license](https://github.com/ctripcorp/apollo/blob/master/LICENSE).

## Known Users

按照登记顺序排序，更多接入公司，欢迎在[https://github.com/douyu/juno/issues/43](https://github.com/douyu/juno/issues/43) 登记（仅供开源用户参考）

<table>
<tr>
<td>斗鱼</td>
</tr>
</table>
