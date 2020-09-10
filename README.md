# sql_wordpress
consulta de sql utiles en wordpress
SELECT post_id, meta_key, meta_value FROM wp_postmeta WHERE post_id IN (35) ORDER BY meta_id ASC
SELECT post_id FROM wp_postmeta WHERE meta_key='_sku' AND meta_value='wp-pennant'
