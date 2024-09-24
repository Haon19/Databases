SELECT country.name, count(*)
FROM country, airport
WHERE country.iso_country = airport.iso_country
GROUP BY country.name
ORDER BY count(*) 
desc limit 50;

[photo](ex6_q5_photo.png)