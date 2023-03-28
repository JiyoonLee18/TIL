# Weather Observation Station 4

- 날짜: 2023.03.15
- 문제: [https://www.hackerrank.com/challenges/weather-observation-station-4/problem?isFullScreen=true](https://www.hackerrank.com/challenges/weather-observation-station-4/problem?isFullScreen=true)

### 문제

Find the difference between the total number of **CITY** entries in the table and the number of distinct **CITY** entries in the table.

The **STATION** table is described as follows:

![Untitled](https://user-images.githubusercontent.com/98992915/228222768-36478035-4162-4054-ab48-138eae4ef860.png)

where **LAT_N** is the northern latitude and **LONG_W** is the western longitude.

### 답

```sql
SELECT  COUNT(*)-COUNT(DISTINCT(CITY))
  FROM  STATION;
```

### 결과

```
# result
13
```
