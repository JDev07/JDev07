1)

select city, country from city

inner join country on city.city_id = country.country_id;

2)

select payment_id, first_name, last_name from customer

inner join payment on payment.customer_id = customer.customer_id;

3)

select rental_id, first_name, last_name from customer

inner join rental on rental.customer_id = customer.customer_id;
