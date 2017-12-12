# Github Issue Viewer

## The Challenge

깃헙 이슈를 볼수 있는 웹을 만드는 프로젝트입니다.
깃헙 API를 이용하여 이슈 정보를 읽어오고 다음 링크들을 참고하시면 됩니다.

- [Github API Documentation](http://developer.github.com/v3/issues/)
- [Github issues data](https://api.github.com/repos/npm/npm/issues)

## 제출 필수 사항

- Minify되지 않은 Javascript/CSS
- Static Assets
- 프로젝트를 설명하는 README.md (접근 방법, 어려웠던 점, 문제 해결 방법, 기술 스택 그리고 해당 스택 선택 이유 등)
  
## 필수 사항

### 기본 페이지

기본 페이지는 위에 주어진 [npm 프로젝트의 깃헙 이슈 리스트](https://api.github.com/repos/npm/npm/issues)를 보여주어야 합니다. 이슈가 많다면, 페이지별로 나뉘어서 볼 수 있어야 합니다. 보통 큰 프로젝트들은 수백개의 이슈들이 있습니다. 그럴 경우, 모든 이슈들을 찾아볼 수 있어야 합니다.

기본 페이지에서 각각의 이슈는 다음 정보들을 보여주어야 합니다.
- Issue number와 title
- Labels
- 작성자의 user name과 avatar
- 이슈 내용의 첫 140자 (끝맺음은 빈칸 단위로 맺어져야 하며, 140자가 넘을 수는 없습니다.)

### 이슈 세부 정보 페이지

기본 페이지에서 각각의 이슈를 클릭했을 경우, 세부 정보 페이지로 이동해야 합니다. 세부 정보 페이지에서는 다음 사항들을 보여주어야 합니다.

- Issue title과 state
- Labels
- 작성자의 user name과 avatar
- Issue 사항 전문

만약 해당 이슈에 코멘트가 있다면, 코멘트 정보도 가져와서 이슈 세부 정보 페이지 하단에 보여주어야 합니다.
코멘트에서 사용자 이름을 멘션한 경우가 있다면(@-notation), 해당 사용자의 깃헙 페이지로 링크를 걸어주어야 합니다.

## Engineering

원하는 프레임워크나 라이브러리를 자유롭게 선택해주세요. 다만 본인의 실력이 가장 잘 보여질 수 있게, 그리고 최대한으로 좋은 코드(효율, 가독성 등)를 쓰도록 노력해주세요.

## Styling

HTML과 CSS는 자유롭게 해주세요. Foundation이나 Bootstrap을 사용하셔도 좋지만, 저희는 본인만의 창의적인 스타일을 보여주시기를 더 원합니다.
