select country.name AS "country_name", airport.name AS "airport_name"
from airport,country 
where airport.iso_country = country.iso_country and country.continent = 'AN';

[photo](Week3_q3_photo.png)