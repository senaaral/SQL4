# SQL4
SELECT DISTINCT replacement_cost FROM film;

SELECT COUNT(DISTINCT replacement_cost) FROM film;

SELECT COUNT(*) FROM film

WHERE title LIKE 'T%' AND rating = 'G';

SELECT COUNT(DISTINCT country) FROM country

WHERE LENGTH(country) = 5;

SELECT COUNT(*) FROM city

WHERE city ILIKE '%r';
