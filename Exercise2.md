# Exercise 2

## Question 01
select * from goal;

![screenshot_q1](ex2_q1.png)

## Question 02
select name
from airport
where iso_country = "FI";

![screenshot_q2 part 1](ex2_q2-1.png)
![screenshot_q2 part2](ex2_q2-2.png)
![screenshot_q2 part3](ex2_q2-3.png)

## Question 03
select name
from airport
where iso_country = "FI"
order by name;

![screenshot_q3](ex2_q3.png)
- Due to un-ability to take long screenshots, the above screenshot of the output is not complete.

## Question 04
select name, type
from airport
where iso_country = "FI"
order by type, name;

![screenshot_q4](ex2_q4.png)
- Due to un-ability to take long 
screenshots, the above screenshot of the 
output is not complete.

## Question 05
select name
from country
where name like "F%";

![screenshot_q5](ex2_q5.png)

## Question 06
select name
from country
where name like "%f%";

![screenshot_q6](ex2_q6.png)

## Question 07
select location
from game
where screen_name = "Vesa";

![screenshot_q7](ex2_q7.png)

## Question 08
select co2_consumed
from game
where screen_name = "Ilkka";

![screenshot_q8](ex2_q8.png)

## Question 09
select distinct co2_budget
from game;

![screenshot_q9](ex2_q9.png)

## Question 10
select screen_name, 
co2_budget, 
co2_consumed, 
@co2_left := co2_budget - co2_consumed as co2_left 
from game 
where screen_name = "Ilkka";

![screenshot_q10](ex2_q10.png)