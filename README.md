# graph-ql-practice

## reference

1. [DashBoard](https://www.youtube.com/watch?v=jx5hdo50a2M)

## 사용 API 리스트

```js
// YTS.MX
  https://yts.mx/api
  https://yts.mx/api/v2/list_movies.json

// Twitter API
  https://developer.twitter.com/en/docs/api-reference-index
```

## REST API과 비교한 GraphQL 장점

1. Overfetching을 개선한 Query
   - 필요한 쿼리 데이터만 Fetching 가능
2. Underfetching
   - 전체 리스트 query/상세 리스트 query 등 필터에 대한 API를 추가적으로 Request해야함. 점점 더 많을 수도.
   - GraphQL은 이를 개선해서 여러 개 URL이 아닌, 하나의 URL을 통해 받을 수 있음.
