# Deploying Oracle Kubernetes Engine.

## Table of Contents

[Overview](#overview)

[Pre-Requisites](#pre-requisites)

[Sign in to OCI Console and create a VCN](#sign-in-to-oci-console-and-create-a-vcn)

## Overview

test test test

**Some Key points;**

***Recommended Browsers: Chrome, Edge**

- We recommend using Chrome or Edge as the broswer. Also set your browser zoom to 80%

- All screen shots are examples ONLY. Screen shots can be enlarged by Clicking on them

- Login credentials are provided later in the guide (scroll down). Every User MUST keep these credentials handy.

- Do NOT use compartment name and other data from screen shots.Only use  data(including compartment name) provided in the content section of the lab

- Mac OS Users should use ctrl+C / ctrl+V to copy and paste inside the OCI Console

- Login credentials are provided later in the guide (scroll down). Every User MUST keep these credentials handy.

**Cloud Tenant Name**
**User Name**
**Password**
**Compartment Name (Provided Later)**

**Note:** OCI UI is being updated thus some screenshots in the instructions might be different than actual UI

## Pre-Requisites

1. OCI Training : https://cloud.oracle.com/en_US/iaas/training

2. Familiarity with OCI console: https://docs.us-phoenix-1.oraclecloud.com/Content/GSG/Concepts/console.htm

3. Overview of Networking: https://docs.us-phoenix-1.oraclecloud.com/Content/Network/Concepts/overview.htm

4. Familiarity with Compartments: https://docs.us-phoenix-1.oraclecloud.com/Content/GSG/Concepts/concepts.htm

5. Connecting to a compute instance: https://docs.us-phoenix-1.oraclecloud.com/Content/Compute/Tasks/accessinginstance.htm

## Sign in to OCI Console and create a VCN

* **Tenant Name:** {{Cloud Tenant}}
* **User Name:** {{User Name}}
* **Password:** {{Password}}
* **Compartment:** {{Compartment}}

### JAPANESE

Kubernetesは、宣言的な構成管理と自動化を促進し、コンテナ化されたワークロードやサービスを管理するための、ポータブルで拡張性のあるオープンソースプラットホームです。

Kubernetesは膨大で、急速に成長しているエコシステムを備えており、それらのサービス、サポート、ツールは幅広い形で利用可能です。

Googleは2014年にKubernetesプロジェクトをオープンソース化しました。KubernetesはGoogleが大規模な本番ワークロードを動かしてきた10年半の経験と、コミュニティから得られた最善のアイデア、知見に基づいています。


### KOREAN

쿠버네티스는 컨테이너화된 워크로드와 서비스를 관리하기 위한 이식성이 있고, 확장가능한 오픈소스 플랫폼이다. 쿠버네티스는 선언적 구성과 자동화를 모두 용이하게 해준다. 쿠버네티스는 크고, 빠르게 성장하는 생태계를 가지고 있다. 쿠버네티스 서비스, 기술 지원 및 도구는 어디서나 쉽게 이용할 수 있다.

쿠버네티스란 명칭은 키잡이(helmsman)이나 파일럿을 뜻하는 그리스어에서 유래했다. 구글이 2014년에 쿠버네티스 프로젝트를 오픈소스화했다. 쿠버네티스는 구글의 15여년에 걸친 대규모 상용 워크로드 운영 경험을 기반으로 만들어졌으며 커뮤니티의 최고의 아이디어와 적용 사례가 결합되었다.


### French
Kubernetes est une plate-forme open-source extensible et portable pour la gestion de charges de travail (workloads) et des services conteneurisés. Elle favorise à la fois l’écriture de configuration déclarative (declarative configuration) et l’automatisation. C’est un large écosystème en rapide expansion. Les services, le support et les outils Kubernetes sont largement disponibles.

Google a rendu open-source le projet Kubernetes en 2014. Le développement de Kubernetes est basé sur une décennie et demie d’expérience de Google avec la gestion de la charge et de la mise à l’échelle (scale) en production, associé aux meilleures idées et pratiques de la communauté.

### CHINESE

Kubernetes 是一个跨主机集群的 开源的容器调度平台，它可以自动化应用容器的部署、扩展和操作 , 提供以容器为中心的基础架构。

使用 Kubernetes, 您可以快速高效地响应客户需求:

快速、可预测地部署您的应用程序
拥有即时扩展应用程序的能力
不影响现有业务的情况下，无缝地发布新功能
优化硬件资源，降低成本
我们的目标是构建一个软件和工具的生态系统，以减轻您在公共云或私有云运行应用程序的负担。

Kubernetes 具有如下特点:
便携性: 无论公有云、私有云、混合云还是多云架构都全面支持
可扩展: 它是模块化、可插拔、可挂载、可组合的，支持各种形式的扩展
自修复: 它可以自保持应用状态、可自重启、自复制、自缩放的，通过声明式语法提供了强大的自修复能力
Kubernetes 项目由 Google 公司在 2014 年启动。Kubernetes 建立在 Google 公司超过十余年的运维经验基础之上，Google 所有的应用都运行在容器上, 再与社区中最好的想法和实践相结合，也许它是最受欢迎的容器平台。

准备好 开始?

### Spanish

Kubernetes es una plataforma portable y extensible de código abierto para administrar cargas de trabajo y servicios. Kubernetes facilita la automatización y la configuración declarativa. Tiene un ecosistema grande y en rápido crecimiento. El soporte, las herramientas y los servicios para Kubernetes están ampliamente disponibles.

Google liberó el proyecto Kubernetes en el año 2014. Kubernetes se basa en la experiencia de Google corriendo aplicaciones en producción a gran escala por década y media, junto a las mejores ideas y prácticas de la comunidad.

https://www.datocms-assets.com/2885/1568037655-1567721088-terraform-overview-hero-cli.mp4
