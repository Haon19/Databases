SELECT name 
FROM airport
WHERE elevation_ft in(
SELECT max(elevation_ft)
FROM airport);

[photo](ex6_q7_photo.png)