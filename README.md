solution 1:

ALGORITHME sum_array
VAR
set1: ARRAY_OF INTEGERS
set2: ARRAY_OF INTEGERS
i : INTEGER
j : INTEGER
sum : INTEGER
BEGIN
sum:= 0
FOR i FROM 0 TO set1.length-1 STEP1 DO 
FOR j FROM 0 TO set2.length DO
IF (set1[i] <> set2[j]) THEN
  sum = set1[i]+set2[j];
ELSE
  i++
  j++
END_IF  

solution 2:

ALGORITHME sum_hash
VAR
set1: HASCH_TABLE <INTEGER,INTEGER>;
set2: HASCH_TABLE <INTEGER,INTEGER>;
BEGIN
