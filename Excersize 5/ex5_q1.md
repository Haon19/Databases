select country.name
from country
join airport on airport.iso_country = country.iso_country
where airport.name like "Satsuma%";

[photo](ex5_q1_photo.png)