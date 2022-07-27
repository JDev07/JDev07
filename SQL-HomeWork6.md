1)

select AVG(rental_rate) from film

2)

select count(*) from film

where title like 'C%';

3)

select max(lenght) from film

where rental_rate=0.99

4)

select COUNT(DISTINCT replacement_cost) from film
where lenght>150
