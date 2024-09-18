select name
from goal,game,goal_reached
where screen_name = 'Heini' and game.id = game_id and goal.id = goal_id;

[photo]()