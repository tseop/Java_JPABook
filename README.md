CHAPTER 08
===
[ 프록시와 연관관계 관리 ]
---


주요 과정
---

| 주제                 | 내용                                                                                                                                                                                                                       |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 프록시와 즉시로딩, 지연로딩    | 객체는 객체그래프를 통해 데이터를 조회할 수 있다. 다만 실제 데이터는 데이터베이스에 저장되어 있으므로 테이블의 데이터를 조회해야 객체 그래프로 탐색이 가능하다.<br/> JPA는 이러한 문제를 프록시라는 기술을 사용하여 연관된 데이터를 실제 사용하는 시점에 데이터베이스에 조회할 수 있게 해두었는데 <br/>이 기능은 자주 사용하는 객체들은 조인을 통해 데이터를 미리 조회하는 것이다. |
| 영속성 전이와 고아객체       | 연관된 객체를 함께 저장하거나 삭제할 수 있는 기능                                                                                                                                                                                             |


