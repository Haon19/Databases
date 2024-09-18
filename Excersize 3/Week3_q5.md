select (elevation_ft * 0.3048) AS elevation_m 
from airport,game 
where location = ident and screen_name = 'Heini';

[photo]()