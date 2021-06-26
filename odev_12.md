# kodluyoruz_sql_odev_11


## Homework
```
SELECT COUNT(*) FROM film WHERE length > (SELECT AVG(length) FROM film);
SELECT COUNT(*) FROM film WHERE rental_rate = (SELECT MAX(rental_rate) FROM film);
SELECT * FROM film WHERE rental_rate = (SELECT MIN(rental_rate) FROM film) AND replacement_cost = (SELECT MIN(replacement_cost) FROM film);
SELECT customer.customer_id, customer.first_name, customer.last_name, COUNT(*) as shopping_count 
FROM customer JOIN payment ON payment.customer_id = customer.customer_id 
GROUP BY customer.customer_id ORDER BY COUNT(*) DESC;
```
