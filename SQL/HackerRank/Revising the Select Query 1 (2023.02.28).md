# Revising the Select Query I

- 날짜: 2023.02.28
- 문제: [https://www.hackerrank.com/challenges/revising-the-select-query/problem?isFullScreen=true](https://www.hackerrank.com/challenges/revising-the-select-query/problem?isFullScreen=true)

### 문제

Query all columns for all American cities in the **CITY** table with populations larger than `100000`. The **CountryCode** for America is `USA`.

The **CITY** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

### 답

```sql
SELECT  *
  FROM  CITY
 WHERE  POPULATION>100000 AND COUNTRYCODE="USA";
```

### 결

```
# result
3878 Scottsdale USA Arizona 202705
3965 Corona USA California 124966
3973 Concord USA California 121780
3977 Cedar Rapids USA Iowa 120758
3982 Coral Springs USA Florida 117549
```