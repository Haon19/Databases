SELECT screen_name, count(*)
FROM game, goal_reached
where game.id = game_id
group by screen_name;

[photo](ex6_q3_photo.png)