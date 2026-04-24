# TP 3 SQL
## Exo 1
<pre>SELECT 
count(*) AS nb_users
from users;</pre>
## Exo 2
<pre>SELECT 
count(*) AS produits_dispo
from products
WHERE is_available = 1;</pre>
## Exo 3
<pre>SELECT 
    MIN(price) AS prix_minimum,
    MAX(price) AS prix_maximum
FROM products;</pre>
## Exo 4
<pre>SELECT 
    AVG(rating) AS note_moyenne
FROM reviews;</pre>
## Exo 5
<pre>SELECT 
	sum(quantity) AS Quantité_tot
FROM order_items;</pre>
## Exo 6
<pre>SELECT
	status,
	count(*) AS Nb_cmd
FROM orders
group by status
order by Nb_cmd DESC;</pre>
## Exo 7
<pre></pre>
## Exo 8
<pre></pre>
## Exo 9
<pre></pre>
## Exo 10
<pre></pre>
## Exo 11
<pre></pre>
## Exo 12
<pre></pre>
## Exo 13
<pre></pre>
## Exo 14
<pre></pre>
## Exo 15
<pre></pre>
## Exo 16
<pre></pre>
## Exo 17
<pre></pre>
## Exo 18
<pre></pre>
## Exo 19
<pre></pre>
## Exo 20
<pre></pre>
## Exo 21
<pre></pre>
## Exo 22
<pre></pre>
## Exo 23
<pre></pre>
## Exo 24
<pre></pre>
## Exo 25
<pre></pre>
## Exo 26
<pre></pre>
## Exo 27
<pre></pre>
## Exo 28
<pre></pre>
## Exo 29
<pre></pre>
## Exo 30
<pre></pre>
