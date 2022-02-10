# mysql commands

SELECT *
FROM customers
WHERE last_name REGEXP 'B[RU]'
-- WHERE last_name REGEXP '^MY|SE'
-- WHERE last_name REGEXP 'EY$|ON$'
-- WHERE last_name LIKE "%EY" OR last_name LIKE "%ON"
-- WHERE first_name IN ('ELKA', 'AMBUR')
