1)

select * from film

group by rating

2)

select replacement_cost,count(*) from film

group by replacement_cost

having count(*)>50

3)

SELECT store_id, COUNT(*)

FROM customer

GROUP BY store_id;



4)

select  country_id, COUNT(*) from city

group by country_id

order by COUNT(*) DESC

LIMIT 1;
