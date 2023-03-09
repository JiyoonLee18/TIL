# Weather Observation Station 3

- 날짜: 2023.03.09
- 문제: [https://www.hackerrank.com/challenges/weather-observation-station-3/problem?isFullScreen=true](https://www.hackerrank.com/challenges/weather-observation-station-3/problem?isFullScreen=true)

### 문제

Query a list of **CITY** names from **STATION** for cities that have an even **ID** number. Print the results in any order, but exclude duplicates from the answer.The **STATION** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)

where **LAT_N** is the northern latitude and **LONG_W** is the western longitude.

### 답

```sql
SELECT  DISTINCT(CITY)
  FROM  STATION
 WHERE  ID%2=0;
```

### 결과

```
# result
Aguanga 
Alba 
Albany 
Amo 
Andersonville
...
```