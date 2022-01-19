---
title: "[GitHub Blog] 깃허브 블로그 포스팅하는 법"
excerpt: "md 파일에 마크다운 문법으로 작성하여 Github 원격 저장소에 업로드 해보자. 에디터는 VS Code 를 사용했다."

categories: etc
---

# GitHub Blog 포스팅하는 법

**1. 마크다운 에디터를 실행한다.**
- 기존에 Typora 를 사용했지만 VS Code 가 편리해 변경했다.

**2. `yyyy-mm-dd-title.md` 형식의 파일을 만든다.**
- title 은 영어로 작성하는 것을 추천한다.
- 머리말의 `title` 을 작성하지 않을 경우 해당 파일명의 title 이 포스팅 제목이 된다.

**3. Front-Matter (머리말)을 작성한다.**
- `title`, `excerpt`, `category`, `toc` 등의 옵션을 적용하여 작성한다.
- 위 아래에 `---` 구분선으로 머리말임을 구분한다.
- **toc** : Table of Contents. 포스트의 헤더들만 보여주는 목차를 사용할 것인지의 여부. true 로 해주면 포스트의 목차가 보이게 된다.