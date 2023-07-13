---
layout: post
permalink: /kubenetes/part-1
title: Kubenetes (Part-1. 개요)
date: 2021-02-01 00:00:00 +0900
description: Kubenetes # Add post description (optional)
img: logo-kubernetes.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Kubenetes, k8s]
---
# Kubernetes
* 쿠버네티스는 컨테이너화된 워크로드와 서비스를 관리하기 위한 이식성이 있고, 확장가능한 오픈소스 플랫폼입니다.

## Pod
* 파드(Pod) 는 쿠버네티스에서 생성하고 관리할 수 있는 배포 가능한 가장 작은 컴퓨팅 단위입니다.
* 하나 이상의 컨테이너의 그룹이며 스토리지 및 네트워크를 공유하고, 해당 컨테이너를 구동하는 방식에 대한 명세를 갖습니다.

## Deployment
* 디플로이먼트(Deployment) 는 파드와 레플리카셋(ReplicaSet)에 대한 선언적 업데이트를 제공합니다.
* 디플로이먼트에서 의도하는 상태 를 설명하고, 디플로이먼트 컨트롤러(Controller)는 현재 상태에서 의도하는 상태로 비율을 조정하며 변경합니다.

## Service
* 파드 집합에서 실행중인 애플리케이션을 네트워크 서비스로 노출하는 추상화 방법입니다.
* 쿠버네티스는 파드에게 고유한 IP 주소와 파드 집합에 대한 단일 DNS 명을 부여하고, 그것들 간에 로드-밸런스를 수행할 수 있습니다.

## Ingress
* 인그레스는 클러스터 외부에서 클러스터 내부 서비스로 HTTP와 HTTPS 경로를 노출합니다.
* 인그레스는 부하 분산, SSL 종료, 명칭 기반의 가상 호스팅을 제공할 수 있습니다.

# Reference
* [쿠버네티스란 무엇인가?](https://kubernetes.io/ko/docs/concepts/overview/what-is-kubernetes/)
* [파드](https://kubernetes.io/ko/docs/concepts/workloads/pods/)
* [디플로이먼트](https://kubernetes.io/ko/docs/concepts/workloads/controllers/deployment/)
* [서비스](https://kubernetes.io/ko/docs/concepts/services-networking/service/)
* [인그레스](https://kubernetes.io/ko/docs/concepts/services-networking/ingress/)