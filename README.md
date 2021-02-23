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

INSERT INTO Vuelos VALUES (6, '2021/03/07', '18:20', 'Guadalajara', 'Francia', '2', '5')
INSERT INTO Vuelos VALUES (7, '2021/03/14', '00:30', 'Australia', 'Londres', '5', '7')
INSERT INTO Vuelos VALUES (8, '2021/03/21', '15:45', 'Morelia', 'Washington DC', '1', '4')
INSERT INTO Vuelos VALUES (9, '2021/03/28', '11:00', 'Argentina', 'Brasil', '2', '5')
INSERT INTO Vuelos VALUES (10, '2021/03/30', '21:10', 'Tokio', 'Francia', '2', '5')
seleccione * de vuelos; 
INSERT INTO Sucursal VALUES(105, '5 de Mayo # 250', '61-284-214-572')
INSERT INTO Sucursal VALUES(106, 'Wallaby # 422B', '351-185-2191')
INSERT INTO Sucursal VALUES(107, 'Primero de Mayo # 101', '443-250-1802')
INSERT INTO Sucursal VALUES(108, 'Guevara # 20', '54-185-124-1430')
INSERT INTO Sucursal VALUES(109, 'Huan Xiu Shang #4512', '011-712-381-1079')






