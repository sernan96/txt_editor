# txt-
C, ubuntu에서 작성 및 실행

## 구현기능
1.줄 단위 출력
1)  명령 줄 인수로 받은 텍스트 파일을 검사하여 사용자가 원하는 줄을 출력하는 프로그램 을 작성하시오. 
2)  이 프로그램은 시작하면 프롬프트를 내주며 사용자가 원하는 줄 번호를 입력 받아 해당 줄을 줄 번호와 함께 출력한다. 
3)  줄 번호는 다음과 같은 4가지 형태로 입력할 수 있다.
n   한 줄 번호
n, ..., m 줄 번호 리스트
n-m 줄의 범위
*   모든 줄

2. 라인 에디터로 확장
1. 줄 단위 출력 프로그램을 간단한 편집 기능을 갖는 라인 에디터로 확장
2. 편집 명령어 설계
-    프린트
•      p 줄번호
-    줄 삭제
•      d 줄번호
-    줄 추가
•      a 줄번호
•      줄번호 이후에 추가할 줄 입력
-    줄 대치
•      s 줄번호
•      해당 줄을 대치할 줄 입력
