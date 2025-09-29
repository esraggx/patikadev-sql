#Answers:

1-
```sql
SELECT DISTINCT replacement_cost FROM film
```
2-
```sql
SELECT COUNT(DISTINCT replacement_cost) FROM film
```
3-
```sql
SELECT COUNT(*) FROM film
WHERE title LIKE 'T%' AND rating = 'G';
```
4-
```sql
SELECT COUNT(*) FROM country
WHERE country LIKE '_____'
```
5-
```sql
SELECT COUNT(*) FROM city
WHERE city ILIKE '%r';
```
