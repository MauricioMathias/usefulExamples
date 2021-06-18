# usefulExamples
Conexão PostgresSQL de um banco a partir de outro banco:
select * from dblink($a$host=*dbIP* dbname=*dbName* user=*user* password=*password*$a$,$b$
SELECT
(SELECT COUNT(DISTINCT -----) as ---,
-----, -----
       FROM ----
          WHERE ----- IS NULL
  group by -----    
  order by -----
  desc limit 1)
$b$) as ----- (----- smallint)
    $$);
SELECT * FROM -------(-----);

SELECT DISTINCT ------,
    ------,
      -----
       FROM ------
          WHERE ------- IS NULL
  group by -----
