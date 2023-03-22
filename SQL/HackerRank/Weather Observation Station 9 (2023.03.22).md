# Weather Observation Station 9

- 날짜: 2023.03.22
- 문제: [https://www.hackerrank.com/challenges/weather-observation-station-9/problem?isFullScreen=true](https://www.hackerrank.com/challenges/weather-observation-station-9/problem?isFullScreen=true)

### 문제

Query the list of *CITY*  names from **STATION**  that *do not start* with vowels. Your result cannot contain duplicates.

**Input Format**

The **STATION** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)

where *LAT_N* is the northern latitude and *LONG_W* is the western longitude.

### 답

```sql
SELECT  DISTINCT(CITY)
  FROM  STATION
 WHERE  CITY NOT REGEXP '^[A,E,I,O,U]';
```

### 결과

```
# result
Kissee Mills
Loma Mar
Sandy Hook
Tipton
Turner
...
```

참고

[https://steemit.com/mysql/@seobangnim/mysql-regexp](https://steemit.com/mysql/@seobangnim/mysql-regexp)