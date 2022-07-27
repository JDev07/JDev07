1-)
Select city.city, country.country From city
LEFT JOIN country ON country.country_id = city.country_id;

2-)
Select payment.payment_id, customer.first_name, customer.last_name from customer
RIGHT JOIN payment ON customer.customer_id = payment.customer_id ;

3-)
Select rental.rental_id, customer.first_name, customer.last_name from customer
FULL JOIN rental ON customer.customer_id = rental.customer_id ;
