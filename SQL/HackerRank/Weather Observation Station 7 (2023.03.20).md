# Weather Observation Station 7

- 날짜: 2023.03.20
- 문제: [https://www.hackerrank.com/challenges/weather-observation-station-7/problem?isFullScreen=true&h_r=next-challenge&h_v=zen&h_r=next-challenge&h_v=zen](https://www.hackerrank.com/challenges/weather-observation-station-7/problem?isFullScreen=true&h_r=next-challenge&h_v=zen&h_r=next-challenge&h_v=zen)

### 문제

Query the list of *CITY* names ending with vowels (a, e, i, o, u) from **STATION**. Your result *cannot* contain duplicates.

**Input Format**

The **STATION** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)

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
