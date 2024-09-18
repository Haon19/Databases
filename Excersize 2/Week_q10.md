SET @co2_left := (select co2_budget from game where screen_name = 'Ilkka') - (select co2_consumed from game where screen_name = 'Ilkka');

select screen_name,co2_consumed,co2_budget,@co2_left from game where screen_name = "Ilkka";

[photo](Week_q10_photo.png)