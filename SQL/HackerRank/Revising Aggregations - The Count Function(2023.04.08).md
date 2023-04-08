# Revising Aggregations - The Count Function

- 날짜: 2023.04.05
- 문제: [https://www.hackerrank.com/challenges/revising-aggregations-the-count-function/problem?isFullScreen=true](https://www.hackerrank.com/challenges/revising-aggregations-the-count-function/problem?isFullScreen=true)

### 문제

Query a *count* of the number of cities in **CITY** having a *Population* larger than .

**Input Format**

The **CITY** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

### 답

```sql
SELECT  COUNT(*)
  FROM  CITY
 WHERE  POPULATION>100000;
```

### 결과

```
# result
6
```