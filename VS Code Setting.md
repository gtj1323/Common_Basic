[TOC]

VS Code는 Extensions, setting.json파일 수정을 통해서 개발환경을 커스텀할 수 있다.

# 1. Extensions (확장프로그램)

- Python
  Python Code(.py파일)을 알아 보기 좋게 만들어줌. (칼라풀하게 알지?)
- Material Icon Theme , vscode-icons
  VS Code상에 표시되는 파일의 색상과 모양을 수정해줌. 둘 중 하나만 쓰면 됨.
- Auto Close Tag
  웹 개발 시에 `Alt`+`.` 단축키를 통해서 자동을 태그를 닫는 확장프로그램.
- Auto Rename Tag
  태그이름의 양 끝을 동시에 바꿔주는 확장프로그램.
- Bracket Pair Colorizer
  짝이 되는 괄호끼리 색을 구분하여 칠해주는 확장프로그램.
- Debugger for Chrome
  크롬 디버거를 VS Code로 가져다줌.
- Highlight Matching Tag
  짝이 되는 태그 끼리 색을 입혀 구분을 편하게 해줌.
- Git History
  Git 사용을 편하게 해줌.
  1. `Ctrl`+`Shift`+`P` or `F1`을 통해서 사용자 팔레트를 연다.
  2. Git Log를 입력.
  3. Git : View History 항목을 선택한 뒤 엔터.
- Korean Language Pack for Visual Studio Code
  VS Code 한글화.
- Markdown All in One
  마크다운 문법을 편하게 사용 가능.
- JSON Tools
  json 문자열 정렬을 간편하게 해줌. `Ctrl`+`Alt`+`M`.
- Prettier - Code formatter
  자동정렬 포멧을 지원.

# 2. setting.json (커스텀 세팅)

- 서체 적용 방법
  1) 서체 설치
  2) Setting.json 으로 들어가서 수정. (`Ctrl`+`Shift`+`P`에서 찾을 수 있다.)
      아래 예시는 Fira Code 적용 예

  ```
  "[python]": {
      "editor.fontFamily": "Fira Code",
      "editor.fontLigatures": true,
},
  ```
  
- 

# 3. VS Code 단축키

VS Code API 문서 : https://demun.github.io/vscode-tutorial/shortcuts/