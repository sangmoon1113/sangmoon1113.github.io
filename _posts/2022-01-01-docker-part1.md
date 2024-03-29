---
layout: post
permalink: /docker/part-1
title: Docker (Part-1. 개요)
date: 2021-01-01 00:00:00 +0900
description: Docker # Add post description (optional)
img: logo-docker.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [docker, container]
---
# Docker
* 소프트웨어를 컨테이너로 패키징 하여, 이 컨테이너에는 라이브러리, 시스템 도구, 코드, 런타임 등 소프트웨어를 실행하는 데 필요한 모든 것 이 포함되어 있습니다.

## Docker Container
* 예전의 가상 머신(Virtual Machine)이 하드웨어를 가상화 하듯이, 컨테이너는 운영 체제를 가상화 합니다.


## Container Image
* 컨테이너를 만드는 데 필요한 모든 종속성 및 정보를 포함한 패키지입니다. 

## Dockerfile
* 이미지를 빌드하기 위한 지침을 포함하는 텍스트 파일입니다. 
* 배치 스크립트처럼 첫 번째 줄에 지정된 기본 이미지에서 시작한 다음, 필요한 작업 환경이 완성될 때까지 지침에 따라 필요한 프로그램을 설치하고 파일을 복사하는 등의 작업을 수행합니다.

## Build
* 해당 Dockerfile에서 제공하는 정보 및 컨텍스트에 외에도 이미지를 빌드하는 폴더의 추가 파일에 기반하여 컨테이너 이미지를 빌드하는 작업

## Container
* Docker 이미지의 인스턴스입니다. 컨테이너는 단일 애플리케이션, 프로세스 또는 서비스의 실행을 나타냅니다.

## Volume
* 컨테이너가 사용할 수 있는 쓰기 가능한 파일 시스템을 제공합니다.

## Tag
* (버전 번호 또는 대상 환경에 따라) 다양한 이미지 또는 동일한 이미지의 버전을 식별할 수 있도록 합니다.

## Repository
* 이미지 버전을 나타내는 태그를 사용하여 이미지가 지정된 관련 Docker 이미지의 컬렉션입니다.

## Registry
* 리포지토리에 대한 액세스를 제공하는 서비스입니다.

# Reference
* [Docker](https://www.docker.com/)
* [Docker란 무엇인가요?](https://docs.microsoft.com/ko-kr/dotnet/architecture/microservices/container-docker-introduction/docker-defined)
* [Docker 용어](https://docs.microsoft.com/ko-kr/dotnet/architecture/microservices/container-docker-introduction/docker-terminology)