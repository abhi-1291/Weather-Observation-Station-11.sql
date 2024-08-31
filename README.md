SELECT DISTINCT(CITY)
<br>
FROM STATION
<br>
WHERE
<br>
LEFT(CITY,1) NOT IN ('A', 'E', 'I', 'O', 'U')
<br>
OR
<br>
RIGHT(CITY,1) NOT IN ('A', 'E', 'I', 'O', 'U');
