# Japanese Cities' Names

- 날짜: 2023.03.06
- 문제: [https://www.hackerrank.com/challenges/japanese-cities-name/problem?isFullScreen=true](https://www.hackerrank.com/challenges/japanese-cities-name/problem?isFullScreen=true)

### 문제

Query the names of all the Japanese cities in the **CITY** table. The **COUNTRYCODE** for Japan is `JPN.`

The **CITY** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

### 답

```sql
SELECT  NAME
  FROM  CITY
 WHERE  COUNTRYCODE="JPN";
```

### 결과

```
# result
Neyagawa
Ageo
Sayama
Omuta
Tokuyama
```