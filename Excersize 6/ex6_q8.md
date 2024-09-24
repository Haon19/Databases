SELECT country.name 
FROM airport,country
WHERE country.iso_country = airport.iso_country AND 
elevation_ft in(
SELECT max(elevation_ft)
FROM airport);

[photo](ex6_q8_photo.png)