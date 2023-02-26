# Select By ID

- 날짜: 2023.02.26
- 문제: [https://www.hackerrank.com/challenges/select-by-id/problem?isFullScreen=true](https://www.hackerrank.com/challenges/select-by-id/problem?isFullScreen=true)

### 문제

Query all columns for a city in **CITY** with the *ID* `1661`.

The **CITY** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

### 답

```sql
SELECT  *
  FROM  CITY
 WHERE  ID=1661;
```

### 결

```
# result
1661 Sayama JPN Saitama 162472
```