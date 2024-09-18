select airport.name
from airport
join country on country.iso_country = airport.iso_country
where country.name = "Monaco";

[photo](ex5_q2_photo.png)