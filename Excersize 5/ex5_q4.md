select country.name
from country
where iso_country not in
(select airport.iso_country
from airport);

[photo](ex5_q4_photo.png)