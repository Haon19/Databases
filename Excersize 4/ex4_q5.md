select goal.name, game.screen_name
from goal
left join goal_reached on goal_id = goal.id
left join game on game.id = game_id;

[photo](ex4_q5_photo.png)