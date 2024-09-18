select game.screen_name, country.name
from game, airport
join country on airport.iso_country = country.iso_country
where location = ident;

[photo](ex4_q3_photo.png)