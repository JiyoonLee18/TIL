# Weather Observation Station 6

- 날짜: 2023.03.18
- 문제: [https://www.hackerrank.com/challenges/weather-observation-station-6/problem?isFullScreen=true](https://www.hackerrank.com/challenges/weather-observation-station-6/problem?isFullScreen=true)

### 문제

Query the list of *CITY* names starting with vowels (i.e., `a`, `e`, `i`, `o`, or `u`) from **STATION**. Your result *cannot* contain duplicates.

**Input Format** The **STATION** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)

where *LAT_N* is the northern latitude and *LONG_W* is the western longitude.

### 답

```sql
SELECT  CITY
  FROM  STATION
 WHERE  CITY REGEXP '^[A,E,I,O,U]';
```

### 결과

```
# result
Acme 
Addison 
Agency 
Aguanga 
Alanson 
Alba
...
```