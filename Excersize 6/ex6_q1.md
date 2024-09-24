SELECT elevation_ft AS 'max(elevation_ft)'
FROM airport 
WHERE elevation_ft in(
SELECT max(elevation_ft)
FROM airport);

[photo](ex6_q1_photo.png)