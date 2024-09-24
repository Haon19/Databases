SELECT country.name
FROM airport, country
WHERE country.iso_country = airport.iso_country
GROUP BY country.iso_country
HAVING count(*) > 1000;

[photo](ex6_q6_photo.png)