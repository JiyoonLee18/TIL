# Weather Observation Station 2

- 날짜: 2023.03.07
- 문제: [https://www.hackerrank.com/challenges/weather-observation-station-2/problem?isFullScreen=true](https://www.hackerrank.com/challenges/weather-observation-station-2/problem?isFullScreen=true)

### 문제

Query a list of **CITY** and **STATE** from the **STATION** table.

The **STATION** table is described as follows:

Query the following two values from the **STATION** table:

1. The sum of all values in *LAT_N* rounded to a scale of  decimal places.
2. The sum of all values in *LONG_W* rounded to a scale of  decimal places.
3. 

**Input Format**

The **STATION** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)

where **LAT_N** is the northern latitude and **LONG_W** is the western longitude.

**Output Format**

Your results must be in the form:

```
lat lon
```

where  is the sum of all values in *LAT_N* and  is the sum of all values in *LONG_W*. Both results must be rounded to a scale of  decimal places.

### 답

```sql
SELECT  ROUND(SUM(LAT_N), 2), ROUND(SUM(LONG_W), 2)
  FROM  STATION;
```

### 결과

```
# result
42850.04 47381.48
```