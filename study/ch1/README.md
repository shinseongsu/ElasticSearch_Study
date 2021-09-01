1. 엘라스틱서치와 키바나를 먼저 설치해줍니다.
   

![elasticsearch](resource/elasticsearch.png)

![kibana](resource/kibana.png)

키바나와 엘라스틱서치를 설치하여 실행하게 되면 위에와 같이 로그와 함께 실행이 된다.


- 키바나 홈페이지 들어가기
키바나 홈페이지에 들어갈려면 ```localhost:5601``` 로 접속을 한다.

![homepage](./resource/kibana_home.png)

홈페이지의 DEV Tool 에서 엘라스틱서치를 실행해볼 수 있다.

![PUT](./resource/index_PUT.png)

```
PUT 인덱스명
{
    json키 : value
}
```

RDB 처럼 테이블을 만들 수 있다.
엘라스틱 서치에서는 도큐먼트라고 부른다.

![GET](./resource/index_GET.png)

```
GET 인덱스명
```

GET 명령어를 이용하여 도큐먼트를 조회할 수 있다.

![SEARCH](./resource/index_SEARCH.png)

search라는 DSL쿼리를 이용해 도큐먼트를 읽어올 수 있다.