Soru 1 Cevap :
select city, country from city
inner join country on city.country_id = country.country_id; <br>
Soru 2 Cevap :
select first_name, last_name, payment_id from  customer
inner join payment on customer.customer_id = payment.customer_id; <br>
Soru 3 Cevap :
select first_name, last_name, rental_id from  customer
inner join rental on customer.customer_id = rental.customer_id; <br>
