---
layout: post
title: Jenkins Pipeline 설정방법(git)
comments: true
categories: Jenkins
date:   2020-01-29 15:29:54
---

## Jenkins Pipeline 설정

![Menu](/static/img/pipeline_jenkins_01.png)

1.New Item 클릭

![Menu](/static/img/pipeline_jenkins_02.png)

2.Pipline 클릭

![Menu](/static/img/pipeline_jenkins_03.png)

3.git Project url 입력(연동할 레파지토리 주소 복사해서 입력)

![Menu](/static/img/pipeline_jenkins_04.png)

4.git업데이트시 자동 빌드설정(* *  * * * 입력)

![Menu](/static/img/pipeline_jenkins_05.png)

5.Pipeline 설정
Repository URL에는 git Repository주소 뒤에 .git을 추가하여 입력
Credentials는 add를 눌러 아래의 양식으로 작성하여 추가

![Menu](/static/img/pipeline_jenkins_06.png)

Credentials 추가양식
