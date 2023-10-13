## 작성한 SQL 파일을 실행하는 방법
1. VSCode에서 터미널을 연다.(터미널을 열고 과제 폴더로 이동해도 됨)
2. MariaDB에 접속한다.(```mysql -u(유저명) -p(비밀번호)```)
3. ```USE (DB이름)```을 통해 DB를 설정
4. ```SOURCE (파일명)```을 통해 소스 코드를 실행한다. 예를 들어, chap4 폴더의 ex4_1.sql을 실행하는 명령어는 다음과 같다.
```
SOURCE chap4/ex4_1.sql
```
5. 만약 테이블이 이미 존재하여 "Table 'students' already exists" 에러가 발생한다면 ```DROP TABLE students```처럼 명령어를 통해 테이블을 제거하고 다시 실행한다.
