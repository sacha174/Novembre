lundi 25 - 11

modélisation dune base de donnée boleen : variable a deux valeur ex : oui ou non

date d’appel sql view : creation de table temporaire

realiser ça sur workbench :

USE Simplon;

Create table contact (id INTEGER PRIMARY KEY auto_increment, prenom varchar(255), nom varchar(255) ,age int(11) , email varchar(255));

insert into contact (id , prenom , nom , age , email) values (1, 'Samba' , 'Cisse' , 54 , 'samba.cisse.data@gmail.com') ;
