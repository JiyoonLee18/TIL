# Japan Population

- 날짜: 2023.04.12
- 문제: [https://www.hackerrank.com/challenges/japan-population/problem?isFullScreen=true](https://www.hackerrank.com/challenges/japan-population/problem?isFullScreen=true)

### 문제

Query the sum of the populations for all Japanese cities in **CITY**. The *COUNTRYCODE* for Japan is **JPN**.

**Input Format**

The **CITY** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

### 답

```sql
SELECT  SUM(POPULATION)
  FROM  CITY
 WHERE  COUNTRYCODE='JPN';
```

### 결과

```
# result
879196
```