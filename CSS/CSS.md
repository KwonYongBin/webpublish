## 1. CSS - HTML로 생성된 틀에 모양, 스타일을 입히는 속성
- HTML 태그에 속성으로 추가하거나, 별도의 파일로 분리하여 생성

## 2. 사용법
- Inline 방식 : HTML 태그에 style 속성을 추가하여 작성
    syntax> style = "프로퍼티 : 값;"
- Internal 방식 : HTML 파일의 head 태그에 페이지에서 호출되는 style 속성 정리
- *(선호) External 방식 : style 속성을 별도의 파일로 생성하여 호출
- [적용 속도는 Internal 방식이 빠르다]

## 3. Internal, External 방시의 문법
- 형식 : 선택자(Selecter) {프로퍼티{Property} : 값(value);};
- selecter 종류 : HTML 태그명, Class(.), Id(#)