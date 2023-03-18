# Weather Observation Station 5

- 날짜: 2023.03.18
- 문제: [https://www.hackerrank.com/challenges/weather-observation-station-5/problem?isFullScreen=true](https://www.hackerrank.com/challenges/weather-observation-station-5/problem?isFullScreen=true)

### 문제

Query the two cities in **STATION** with the shortest and longest *CITY* names, as well as their respective lengths (i.e.: number of characters in the name). If there is more than one smallest or largest city, choose the one that comes first when ordered alphabetically.The **STATION** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)

where **LAT_N** is the northern latitude and **LONG_W** is the western longitude.

### 답

```sql
SELECT CITY, LENGTH(CITY)
  FROM STATION
 ORDER BY LENGTH(CITY), CITY
 LIMIT 1;

SELECT CITY, LENGTH(CITY)
  FROM STATION
 ORDER BY LENGTH(CITY) DESC, CITY
 LIMIT 1;
```

### 결과

```
# result
Amo 3
Marine On Saint Croix 21
```