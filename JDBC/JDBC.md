### JDBC

- 자바에서 DB에 접근하기 위해서는 JDBC가 필수적으로 필요.
- Mysql, Oracle과 같은 다양한 RDBS에 종속되지 않게 DB연결을 하기 위해서 생긴 것이. JDBC 표준 인터페이스  
  

- java.sql.Connection - 연결
- java.sql.Statement - SQL을 담은 내용
- java.sql.ResultSet - SQL 요청 응답

- JDBC는 java.sql.connection 이라는 표준 인터페이스를 정의하고, H2 데이터베이스 드라이버는 JDBC Connection 인터페이스를 구현한다.