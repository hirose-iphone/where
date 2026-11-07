# My Virtual iPhone

순정 iPhone 화면에서 영감을 받은 가상 iPhone 웹사이트 데모입니다. 실제 iOS나 Apple 시스템 기능은 아니며, 브라우저 안에서 동작하는 개인 프로젝트입니다.

## 실행하기
1. ZIP 파일을 압축 해제합니다.
2. `index.html` 파일을 더블클릭합니다.
3. 브라우저에서 잠금 해제 버튼과 앱 아이콘을 눌러 봅니다.

## 파일 구성
- `index.html`: 화면의 구조
- `style.css`: 디자인과 모바일 반응형 레이아웃
- `script.js`: 버튼과 앱의 동작

## GitHub Pages에 공개하기
1. GitHub에 로그인하고 새 저장소(repository)를 만듭니다.
2. 저장소 이름을 `my-virtual-iphone`으로 정합니다.
3. 저장소 공개 범위는 Public으로 선택합니다.
4. Add file → Upload files를 누릅니다.
5. 압축을 푼 폴더 안의 `index.html`, `style.css`, `script.js`를 업로드합니다. ZIP 파일 자체가 아니라 세 파일을 올립니다.
6. Commit changes를 누릅니다.
7. 저장소의 Settings → Pages로 이동합니다.
8. Build and deployment의 Source에서 `Deploy from a branch`를 선택합니다.
9. Branch에서 `main`, 폴더에서 `/(root)`를 선택하고 Save를 누릅니다.
10. 잠시 기다린 뒤 Settings → Pages에 표시되는 사이트 주소를 엽니다.

## 수정하기
- 화면 문구와 앱 내용: `index.html` 또는 `script.js`
- 색상, 크기, 간격: `style.css`
- 앱 동작: `script.js`

## 알아둘 점
GitHub Pages에 게시한 사이트는 인터넷에 공개됩니다. 실제 전화번호, 비밀번호, 주소, 개인 사진 등 민감한 정보는 넣지 마세요. 메시지와 전화 기능은 데모이며 실제 전송/통화가 되지 않습니다.


## 이번 디자인 업데이트
- 잠금 화면의 날짜와 시계를 실제 날짜/시간에 맞춰 표시합니다.
- 기본 iPhone 느낌의 상태 표시줄, 배경화면, 날씨 위젯, 앱 아이콘과 독을 적용했습니다.
- 앱 내부의 메시지, 메모, 전화, 설정은 데모 기능이며 실제 전화·메시지·날씨 서비스와 연결되지 않습니다.
