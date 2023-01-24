---
title: "1월 24일 일기!"
date: 2023-01-24T10:25:03+09:00
# weight: 1
# aliases: ["/first"]
tags: ["일기", "뉴질랜드"]
author: "상현이"
categories: ["일기"]
showToc: true
TocOpen: false
description: "오늘의 경험과 생각"
cover:
    image: #"/blue_lake_2.jpeg" # image path/url
    alt: #"파랑파랑한 호수" # alt text
    caption: #"파랑파랑한 호수" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/spark-in-you/sanghyun.me/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---
## 뉴질랜드에서 마지막날
역시 난 일기 체질이 아니군! 지난 일주일간 엄청 지루해 했으면서도 일기보단 잠을 택했어. 지금은 비행기인 데다가 잠도 안와서 쓰는거란 말이지. 지금은 뉴질랜드 크라이스트처치-오클랜드 간 국내선이고, 오클랜드에서 하룻밤 잔 다음에 한국행 비행기를 타. 11시간짜리 비행인데 머하지? 이미 영화 틀어놓고 스타듀밸리 하다가 잠들듯 해.
- - - -
여행이 재밋고 볼게 많긴 했는데 너어무 오래 있었더니 너무너무 지루해. 드디어 귀국하는게 너무 기대될 정도. 물론 귀국하면 해야할일이 생기긴 하지. 논문쓰기… 졸연 논문 Result 부분 남았는데 아무리 봐도 내가 쓰긴 좀 무리란 말이지. 근데 개강 전에 완성해야하니… 해야지 뭐
## 웹사이트에 대해 이것저것
혹시 나중에 웹사이트를 다기 구축할 일이 생기는걸 대비해 지금 생각나는것들 한번 정리. 지금 이 사이트는 블로그 전문 site generator인 [Hugo](https://gohugo.io) 기반으로 생성된 것이고, 템플릿은 Hugo PaperMod이야. 원래는 오라클 A1 서버에서 Hugo까지 같이 해서 돌렸지만, [github pages](https://pages.github.com)랑 [cloudflare의 pages](https://pages.cloudflare.com)라는 유용한 기능을 발견하고 갈아탔지. 근데 기억상 cloudflare pages에서는 도메인 설정이 잘 안됐던가..? 느렸던가..? 렌더링 제약이 많았던가..? 해서 최종적으로는 github에서 돌아가고 있어. 월 300회 제한이 있으니 주의할 것. 근데 30회 채우기도 쉽지 않더라…
- - - -
컨텐츠 작성은 노트북 vs code에서 깃허브 repo 동기화해서 사용중이야. 원래는 오라클 서버에서 도커 code server로 했는데, 실수로 터트리는 바람에… 근데 로컬에서 하니까 파일시스템에 직접 접근 가능해서 사진 첨부하기가 무지 편하더라고.
- - - -
사진 하니까 생각난건데, Hugo는 전부 markdown 기반이야. Syntax 맨날 헷갈리긴 하는데 그래도 vs code 확장프로그램 설치하면 일반 키보드 단축키 (control-b 라던가) 들이 잘 먹혀서 그냥그냥 쓰는 중. 다만 사진 관련해서 내가 직접 해상도, 크기, 용량 등 설정해야 하는게 좀 귀찮더라고. 근데 그냥 편집기에서 최저 품질로 바꾸면 돼!
- - - -
첨에는 wordpress를 했는데, 왜 버렸냐면, 매우매우 느리기 때문이였어. 아무래도 dynamic이 static보다 훨씬 느리긴 한데, 답답할 정도여서 버렸지. 나중에 이거 잊고 다시 눈돌리는 일 없도록. 차리리 바꾼다면 [Ghost](https://ghost.org) 한번 해봐.
## 애플뮤직이 짜증난다
아니 어제까지만 해도 잘 되다가, 비행기 타니까 다운로드한 곡들이 재생 안되기가 어딧지?? 웃긴건 Stay with me 딱 하나만 잘 재생되서 그거 무한반복 중이야. 담부턴 미리미리 확인하기… 특히 업데이트 후!!!
{{< figure src="staywithme.jpeg" caption="Stay with me" height="400">}}
## iOS 16.3 업데이트
비행기 타기 직전에 업데이트 했는데, 애플뮤직이 망가진거 빼고는 딱히 달라진게 없는거같아. 업데이트 노트에도 딱히 별말 없었음에도 한 이유는!! Icloud advanced data protection이 지원된다고 했기 때문이지. 얼마전까지만 해도 미국에서만 되던건데, 이건 아이클라우드에 올라가는 대부분의 정보(사진을 포함해서!)를 end to end, 즉 종단간 암호화 해주는 기능이야. 전에는 애플이 내 사진을을 볼 수 있었다면, 이제는 암호키를 가진 내가 허용한 기기에서만 볼수 있다 이거지. 뭐 어케보면 그닥 쓸모 없지만 그래도!
![아이클라우드 고급 데이터 보호](/icloud.jpeg#center)
- - - -
아니 것보다 카카오톡은 언제 e2e 지원하는거지??