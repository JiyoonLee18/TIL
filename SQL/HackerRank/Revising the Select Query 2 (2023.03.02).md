# Revising the Select Query 2

- 날짜: 2023.03.02
- 문제: [https://www.hackerrank.com/challenges/revising-the-select-query-2/problem?isFullScreen=true](https://www.hackerrank.com/challenges/revising-the-select-query-2/problem?isFullScreen=true)

### 문제

Query the **NAME** field for all American cities in the **CITY** table with populations larger than `120000`. The *CountryCode* for America is `USA`.

The **CITY** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

### 답

```sql
SELECT  NAME
  FROM  CITY
 WHERE  POPULATION>120000 AND COUNTRYCODE="USA";
```

### 결과

```
# result
Scottsdale
Corona
Concord
Cedar Rapids
```