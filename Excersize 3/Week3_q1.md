select country.name AS 'country name', airport.name AS "airport name" 
from country 
join airport on country.iso_country = airport.iso_country
where country.name = 'Iceland';

[photo](Week3_q1_photo.png)