각각 구현된 기능

공통구현함수 : Run_Program(입력받은 값에 따른 함수 수행), Create_DB(파일이 없을 경우 생성)

list, add, modify, delete 구현

TEST.PY :

정렬순서(출력)가 ID,Category,What,Due,Finished순으로 되어있음.

Finish Y/N 별로 List 출력하는 기능

특정 카테고리만 List 출력하는 기능

Test2.PY :

정렬순서(출력)가 ID,Importance(중요도),Finished,Due,Category,What 순으로 되어있음.

Importance와 Finished는 y,n 입력을 받고, 각각 ★, " " / ○,× 로 표기함(Finished의 기본값은 n)

FirstInteg.py

Test, Test2에 나뉘어 있던 기능 통합 및 신규 함수 추가, 기존 함수 수정

List함수의 구현된 필터 : All, Finish(O/X), Importance(O/X), Category
List함수 수정 : List함수 호출시 원하는 필터를 입력하여 구현하도록 수정하였음.
