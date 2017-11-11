body container grid row col row col...
- 일정하게 맞추기 위한 grid 갯수는 아래 참고
- large screen 12 cols
- mid screen 8 cols
- small screen 4 cols

sass 설치
- npm install -g node-sass 전역
- npm install node-sass 지역

sass 명령어
- node-sass ./sass -o ./css
- sass -> css파일로 변환하여 저장한다.
- node-sass --watch ./sass -o ./css (-w로 써도됨)
- 수정해서 저장할때마다 css에 저절로 반영된다.
- 파일명 _(언더바).scss 일때, 해당 파일의 내용이 전달되지 않는다. -> 다른파일에 import하면 반영된다.
