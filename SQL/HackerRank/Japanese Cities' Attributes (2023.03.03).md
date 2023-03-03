# Japanese Cities' Attributes

- 날짜: 2023.03.03
- 문제: [https://www.hackerrank.com/challenges/japanese-cities-attributes/problem?isFullScreen=true](https://www.hackerrank.com/challenges/japanese-cities-attributes/problem?isFullScreen=true)

### 문제

Query all attributes of every Japanese city in the **CITY** table. The **COUNTRYCODE** for Japan is `JPN`.

The **CITY** table is described as follows:

![https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

### 답

```sql
SELECT  *
  FROM  CITY
 WHERE  COUNTRYCODE="JPN";
```

### 결과

```
# result
1613 Neyagawa JPN Osaka 257315
1630 Ageo JPN Saitama 209442
1661 Sayama JPN Saitama 162472
1681 Omuta JPN Fukuoka 142889
1739 Tokuyama JPN Yamaguchi 107078
```