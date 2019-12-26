# README
우먼테크메이커스 2019 한국 장학생들이 만들고 관리하는 블로그입니다.
Jekyll-powered, Jekflix-theme (아래 Theme Customization 섹션 참고) 웹사이트입니다.

## 글 업로드 가이드
1. _authors/ 폴더 내에 이름_성.md 파일 추가 및 내용 채워 넣기.
2. _posts/ 폴더 내에 year-month-day-title.md 파일 추가 및 내용 채워 넣기.
3. image 업로드하고 싶을 때는 구글 포토 앨범에 추가하기.
4. 로컬에서 작동 확인할 때는
    ```
    npm install
    gulp
    ```
5. 너무 짧은 시간 간격을 두고 업데이트를 하면, 웹사이트가 안 바뀐 것처럼 보일 수도 있는데 그럴 때는 캐시에 저장되어있던 걸 보여줘서 그럴 가능성이 높으니 웹 브라우저 캐시를 지우고 다시 확인해보아요.

## 파일 구조 가이드
* src/yml/: 사이트 테마 설정 파일들 (이 안을 수정하면 gulp를 해야 바깥에 있는 _config.yml도 수정이 되니까 빼먹지 말도록!)
* pages/about.md: 사이트 소개 페이지
* 기타 등등

## 주의사항
* master 브랜치로 force push 막아놓긴 했는데 잘 되었는지는 잘 모르겠어요. 아무튼 force push는 하지 마셔요~
* commit을 깃헙에 올리면 나중에 rebase를 하더라도 찾고자 한다면 과거 기록을 다 찾아낼 수 있으므로 **커밋하기 전에** 민감한 개인 정보를 작성한 것은 아닌지 꼭 확인하고 올리세요! 특히 authors.yml에 글쓴이 등록할 때 실명으로 안 하고 싶다면 필명으로, web, email, image 등 공개하고 싶지 않은 개인 정보는 올리지 마셔요~ 앗, 근데 생각해보니 누가 커밋했는지는 나오겠네요...
* 커밋할 때, 커밋의 내용을 잘 담은 적절한 **커밋 메시지** 작성 부탁합니다!
* 본인 글을 올릴 땐, PR 없이 바로 마스터 브랜치로 커밋해도 괜찮을 것 같아요 (PR로 해도 되구요).
* 만약 다른 사람 글에서 오타 등의 수정 건의 사항 있으면 PR 올리고 글쓴이의 리뷰를 요청하는 방식으로 하면 좋을 것 같아요.
* 이미지 사용시 저작권 등에 주의! (저작권 가이드라인이 있는지 등 확인 후 사용)
* convention은 저희끼리 해보면서 또 정해봅시다. :)

## Theme Customization
* forked from [Jekflix](https://github.com/thiagorossener/jekflix-template) && then customized.
* See the [settings documentation](https://github.com/thiagorossener/jekflix-template/wiki/settings) to customize your theme colors, layout, titles and more.

### Author
[Thiago Rossener](https://rossener.com/)

### License

*Jekflix Template* is available under the MIT license. See the [LICENSE](https://github.com/thiagorossener/jekflix-template/blob/master/LICENSE) file for more info.

### Posts

You can create posts manually using the [Front Matter properties](https://github.com/thiagorossener/jekflix-template/wiki/post#front-matter-properties) or automatically using the available [script](https://github.com/thiagorossener/jekflix-template/wiki/post#creating-a-post).