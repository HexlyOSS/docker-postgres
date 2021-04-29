# Hexly DB 

We love Postgres (particularly on AWS RDS, because we're cowards and running a database is scary) and there's a few extensions we rely heavily on. Most notably, `postgis` and `plv8` (with very specific uses of the latter; please don't put javascript in your database)

Finding docker images with both has been tricky, so this is our contribution to the world. The goal of the `hexlydb` image is to provide a close approximation to extensions found on RDS. 
