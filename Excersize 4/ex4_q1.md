select country.name as 'country name', airport.name as 'airport name'
from country
join airport on airport.iso_country = country.iso_country
where scheduled_service = 'yes' and country.iso_country = 'FI';

[photo](ex4_q1_photo.png)