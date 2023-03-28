# Higher Than 75 Marks

- 날짜: 2023.03.28
- 문제: [https://www.hackerrank.com/challenges/more-than-75-marks/problem?isFullScreen=true](https://www.hackerrank.com/challenges/more-than-75-marks/problem?isFullScreen=true)

### 문제

Query the *Name*  of any student in **STUDENTS**  who scored higher than 75 *Marks*. 

Order your output by the *last three characters* of each name. If two or more students both have names ending in the same last three characters (i.e.: Bobby, Robby, etc.), secondary sort them by ascending *ID*.

**Input Format**

The **STUDENTS**  table is described as follows: 

![Untitled](Higher%20Than%2075%20Marks%20e08c8dc734564764af180c5c70676ef5/Untitled.png)

The *Name* column only contains uppercase (`A`
-`Z`) and lowercase (`a`-`z`) letters.

### 답

```sql
SELECT  NAME
  FROM  STUDENTS
 WHERE  MARKS>75
 ORDER  BY RIGHT(NAME, 3), ID
```

### 결과

```
# result
Stuart
Kristeen
Christene
Amina
Aamina
...
```