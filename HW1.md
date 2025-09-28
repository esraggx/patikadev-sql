#Answers:
----
1-
```sql
select title, description from film
```
2-
```sql
select * from film where length > 60 AND length < 75
```
3-
```sql
select * from film where rental_rate = 0.99 AND 
(replacement_cost = 12.99 OR replacement_cost = 28.99)
```
4-
```sql
select last_name from customer where first_name = 'Mary'
```
5-
```sql
select * from film where length < 50 AND 
rental_rate <> 2.99 AND rental_rate <> 4.99
```
