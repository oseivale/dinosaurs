[See assignment in Alexa](https://alexa.bitmaker.co/wdi/72/assignments/2247/latest)

1) dinosaurs=# SELECT COUNT(id) FROM dinos;
2) SELECT * FROM dinos WHERE period = 'Jurassic';
3) dinosaurs=# SELECT SUM(length) FROM dinos WHERE period = 'Cretaceous';
4) dinosaurs=# SELECT name, species, period from dinos where period ='Cretaceous' or period ='Jurassic' order by name asc;
5) dinosaurs# SELECT name, species from dinos WHERE t_order = 'Saurischia' AND diet = 'Herbivorous';
6) dinosaurs=# update dinos SET name = 'Shortie' WHERE length = (select min(length) from dinos);
UPDATE 1
dinosaurs=# select name, species from dinos where name = 'Shortie';

7) dinosaurs=# SELECT * FROM dinos ORDER BY name asc limit 1;
