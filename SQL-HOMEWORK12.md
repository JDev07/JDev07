
1-
SELECT COUNT(length) FROM film
WHERE length >
(
SELECT AVG(length) FROM film
);

2-

SELECT COUNT(*) FROM film
WHERE rental_rate =
(
SELECT MAX(rental_rate) FROM film
)

3-

SELECT title,rental_rate,replacement_cost FROM film
WHERE rental_rate =
(
SELECT MIN(rental_rate)FROM film	
)
INTERSECT
SELECT title,rental_rate,replacement_cost FROM film
WHERE replacement_cost =
(
SELECT MIN(replacement_cost)FROM film	
);

4-

SELECT customer.first_name,customer.customer_id,COUNT(customer.customer_id) FROM payment
INNER JOIN customer ON customer.customer_id = payment.customer_id
GROUP BY customer.customer_id
ORDER BY COUNT(customer.customer_id) DESC;
