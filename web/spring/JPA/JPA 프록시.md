# 프록시란?
JPA 구현체들은 연관된 객체들 처음부터 데이터베이스에서 조회하는 것이 아니라, 실제 사용하는 시점에 데이터베이스에서 조회할 수  있다. 이와 관련 된 기술이 프록시 인데, 이 프록시를 통해서 즉시로딩 ( EAGER ) 과 지연로딩 ( LAZY ) 을 할 수 있다.



### EntitiyGraph
@EntityGraph는 쿼리가 수행 될 때 LAZY조회가 아니고 EAGER조회로 정보를 가져온다.