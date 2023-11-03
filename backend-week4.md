## 작성한 SQL 파일을 실행하는 방법
주의: SQL 파일을 실행하면 데이터베이스에 반영되므로 반드시 과제 폴더에서 실행할 필요는 없습니다. 또한 테이블을 중복 생성할 경우 오류가 발생하므로 테이블을 초기화하고 싶다면 DROP 명령어를 통해 테이블을 삭제한 다음 다시 생성하세요.
### 1. 파이프 연산자( | )를 이용해서 실행하기

```
cat (파일명) | mysql -u(유저) -p(비밀번호) -D(데이터베이스)
```
예시(5주차 수업 VSCode 터미널에서):```cat ./codes/code_A4.sql | mysql -uroot -ppassword -Dkweb_db```

### 2. MariaDB 내에서 SOURCE 명령어로 실행하기
[3주차 과제](https://github.com/cimkoreauniv/kweb-assignment-details/blob/main/backend_week3.md) 참고

## Exercise 5.1, 5.2 작성 방법
SQL에서 한 줄 주석을 작성하려면 `--`뒤에 내용을 입력하면 됩니다. 그러므로 주석으로 번호를 구분해서 문제 하나 당 하나의 파일에 하나씩 작성해주세요. 아래의 형식을 참고하세요.

[Exercise 5.1](https://github.com/cimkoreauniv/KWEB-assignment-2023-2R/blob/main/chap5/ex5_1.sql)
[Exercise 5.2](https://github.com/cimkoreauniv/KWEB-assignment-2023-2R/blob/main/chap5/ex5_2.sql)
