---
title: 블로그 심폐소생술
date: 2022-12-17T11:30:03+09:00
tags:
  - 잡담
  - 클라우드플레어
  - 도메인
author: 상현
categories:
  - 블로그 개설
showToc: true
TocOpen: false
description: 1년만에 블로그 살리기
cover:
  image: 
  alt: <alt text>
  caption: <text>
  relative: false
  hidden: true
editPost:
  URL: https://github.com/spark-in-you/sanghyun.me/content
  Text: Suggest Changes
  appendFilePath: true
---
# 블로그 살리기
거의 1년만에 돌아온 블로그.
옛날글 대부분 치우고 새로 시작!

우선 오늘 도메인을 뜯어고침. sanghyun.me랑 spark-in-you.com이 계속 결제되고 있는데, 날리기는 좀 아깝지? sanghyun.me는 저번에도 인스타랑 연결하려고 했는데, 이상하게 실패했었음. 
오늘도 한참 걸리긴 했는데 결국 해결.
# 인스타 도메인에 연결하기
나는 외부링크를 root domain에 연결하는 흔치 않은 케이스. 그래도 아이디 눌렀더니 프로필 연결되는건 기분이 좋잖아?
Cloudflare page rule 에서 URL redirect 사용. 다만 여기서 내가 놓친 점은, redirect는 '이미 작동하는' 도메인을 다른 도메인으로 이동시켜 주는 방식이기 때문에, 기존 도메인이 연결조차 되지 않는다면 작동하지 않음.
따라서 [www.sanghyun.me](www.sanghyun.me) 랑 [sanghyun.me](sanghyun.me)를 우선 블로그 cloudflare pages에 연결하고, 다시 인스타그램으로 리다이렉트 시킴. 참고해!