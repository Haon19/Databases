SELECT screen_name
FROM game
WHERE co2_consumed in(
SELECT min(co2_consumed) 
FROM game);

[photo](ex6_q4_photo.png)