select game.screen_name
from game,goal_reached,goal
where game.id = game_id and goal.id = goal_id and goal.name = 'CLOUDS';

[photo](ex5_q3_photo.png)