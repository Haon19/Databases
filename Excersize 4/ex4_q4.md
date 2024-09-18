select airport.name, game.screen_name
from airport
left join game on ident = location
where name like '%hels%';

[photo](ex4_q4_photo.png)