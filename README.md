# Agencia_de_Viajes
create database viajes;
use viajes;
create table Vuelos(
num_vuelo int not null primary key,
fecha date,
hora time,
origen varchar (50),
destino varchar (50),
plazas_tot varchar (50),
plazas_turist varchar (50)
) 
create table sucursal(
cod_sucursal int not null primary key,
direccion varchar (50),
telefono varchar (50)
)
INSERT INTO Vuelos VALUES (1,'2021/02/15','10:30','CDMX','Chicago', '3', '4')
INSERT INTO Vuelos VALUES (2,'2021/02/17','11:30','Rosario','Denver', '2', '4')
INSERT INTO Vuelos VALUES (3,'2021/02/19','12:30','LA','Minesota', '1', '5')
INSERT INTO Vuelos VALUES (4,'2021/02/25','15:30','Monterrey','Canada', '5', '6')
INSERT INTO Vuelos VALUES (5,'2021/02/10','17:30','Italia','España', '2', '5')
select * from vuelos;
INSERT INTO sucursal VALUES (100,'Juarez #200','351-548-65-87')
INSERT INTO sucursal VALUES (101,'La villa #250','654-874-65-98')
INSERT INTO sucursal VALUES (102,'Wall Street #500','845-547-98-74')
INSERT INTO sucursal VALUES (103,'Insurgentes #59','354-875-54-74')
INSERT INTO sucursal VALUES (104,'Via del corso #542','478-874-32-45')
