#***Answers***

1-
```sql
SELECT AVG(rental_rate) FROM film;
```
2-
```sql
SELECT COUNT(*) FROM film
WHERE title LIKE 'C%';
```
3-
```sql
SELECT MAX(length) FROM film 
WHERE rental_rate = 0.99;
```
4-
```sql
SELECT COUNT(DISTINCT(replacement_cost)) FROM film 
WHERE length > 150;
```
