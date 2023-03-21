# Weather Observation Station 8

- 날짜: 2023.03.21
- 문제: [https://www.hackerrank.com/challenges/weather-observation-station-8/problem?isFullScreen=true](https://www.hackerrank.com/challenges/weather-observation-station-8/problem?isFullScreen=true)

### 문제

Query the list of *CITY* names from **STATION** which have vowels (i.e., *a*, *e*, *i*, *o*, and *u*) as both their first *and* last characters. Your result cannot contain duplicates.

**Input Format**

The **STATION** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)

where *LAT_N* is the northern latitude and *LONG_W* is the western longitude.

### 답

```sql
SELECT  DISTINCT(CITY)
  FROM  STATION
 WHERE  CITY REGEXP '[A,E,I,O,U]$' AND
        CITY REGEXP '^[A,E,I,O,U]';
```

### 결과

```
# result
Upperco
Aguanga
East China
East Irvine
Amo
...
```

참고

[https://steemit.com/mysql/@seobangnim/mysql-regexp](https://steemit.com/mysql/@seobangnim/mysql-regexp)