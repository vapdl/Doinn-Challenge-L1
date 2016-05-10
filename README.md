# Doinn-Challenge-L1

![alt tag](http://i67.tinypic.com/5n6gir.png)

### Framework

Laravel 5.1


###Database Structure 

CREATE TABLE `areas` (
  `id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `lat` decimal(10,8) NOT NULL,
  `lng` decimal(11,8) NOT NULL,
  `name` varchar(10) COLLATE utf8_unicode_ci NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=1;


INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.17148113','38.70200622','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.14472341','38.70554786','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.20003986','38.69596523','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.21995258','38.69355360','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.22733402','38.69824281','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.20656300','38.71579113','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.19351673','38.71552324','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.19094181','38.71029937','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.18356037','38.71458565','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.17738056','38.71458565','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.17549229','38.71994315','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.17394733','38.72583593','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.17394733','38.73306732','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.17102909','38.73467419','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.17051411','38.73976239','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.16141605','38.74418080','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.14459324','38.72503240','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.13601017','38.70721844','area 1');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.41101170','38.70185997','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.41598988','38.70038633','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.41856480','38.69797485','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.41993809','38.69623317','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.41839314','38.69382155','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.42028141','38.69154383','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.42165470','38.68980199','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.42714787','38.68980199','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.43487263','38.69234774','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.44036579','38.69516135','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.43573093','38.70078824','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.42869282','38.70547697','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.42010975','38.70681655','area 2');

INSERT INTO `areas` ( `lat`, `lng`, `name` ) VALUES ('-9.41272831','38.70748634','area 2');


###Google Maps

http://maps.google.com/maps/api/geocode/json?sensor=false&address=

