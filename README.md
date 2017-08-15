## 개발자 수다방: 위키

개발자 수다방: 위키(이하 개수다방 위키)의 GitHub 저장소에 오신 것을 환영합니다.

개수다방 위키는 '개발자 수다방' 혹은 '개발자 수다방: 텔레그램 에디션' 채팅방의 참여자라면 누구나 자유롭게 기여하실 수 있습니다.


## 기여하는 법

1. [GitHub 저장소](https://github.com/devroom-org/wiki)를 포크합니다.
1. 포크된 저장소를 clone해서 문서를 만들거나 편집합니다. ('편집하는 법' 참고)
1. push하고 Pull Request를 넣습니다.
1. Pull Request가 승인되면 메인 저장소에 반영됩니다.

## 편집하는 법

* 위키 문서의 소스 파일은 모두 `wiki/` 디렉토리에 있습니다.
* `wiki/` 디렉토리에 **영문 이름**으로 된 파일을 만듭니다.
* 파일 내용 맨 위에 다음과 같이 내용을 추가합니다.

```
---
layout: wiki
permalink: /<링크명 (파일명)>/
title: <(한글) 제목>
---
```

* 문서 내용은 기본적인 Markdown 문법으로 작성하면 됩니다.
* 위키 내부로 가는 링크를 만들려면 주소란을 `{{ site.baseurl }}<링크>`와 같이 작성하면 됩니다.
