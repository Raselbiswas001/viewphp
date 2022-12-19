# viewphp
Great repository names are short and memorable. Need inspiration? How about super-guide?

CREATE VIEW str_product_with_product AS
SELECT str_product_id,str_product_quentity,str_product_entrydate,product_id,product_name
FROM str_product
INNER JOIN product
ON str_product.str_product_name = product.product_id
