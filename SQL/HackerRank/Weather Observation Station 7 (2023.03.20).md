# Weather Observation Station 7

- 날짜: 2023.03.20
- 문제: [https://www.hackerrank.com/challenges/weather-observation-station-7/problem?isFullScreen=true&h_r=next-challenge&h_v=zen&h_r=next-challenge&h_v=zen](https://www.hackerrank.com/challenges/weather-observation-station-7/problem?isFullScreen=true&h_r=next-challenge&h_v=zen&h_r=next-challenge&h_v=zen)

### 문제

where *LAT_N* is the northern latitude and *LONG_W* is the western longitude.

### 답

```sql
SELECT  DISTINCT(CITY)
  FROM  STATION
 WHERE  CITY REGEXP '[A,E,I,O,U]$';
```

### 결과

```
# result
Glencoe
Chelsea
Pelahatchie
Dorrance
Cahone
...
```

참고

[https://steemit.com/mysql/@seobangnim/mysql-regexp](https://steemit.com/mysql/@seobangnim/mysql-regexp)