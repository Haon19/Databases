select country.name
from airport,goal_reached,game,goal,country
where screen_name = 'Ilkka' and game.id = game_id and goal.id = goal_id 
and goal.name = 'CLOUDS' and ident = location and airport.iso_country = country.iso_country;

[photo](Week3_q10_photo.png)