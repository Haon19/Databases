select airport.name
from airport,goal_reached,game,goal
where screen_name = 'Ilkka' and game.id = game_id and goal.id = goal_id 
and goal.name = 'CLOUDS' and ident = location;

[photo]()