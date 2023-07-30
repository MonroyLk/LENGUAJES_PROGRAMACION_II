# LENGUAJES_PROGRAMACION_II
Lenguajes de programación II


create database Act1

USE Act1
CREATE TABLE Empleados (
Num_Empleado VARCHAR (10) NOT NULL,
Nombre VARCHAR(20) NOT NULL,
Apellido VARCHAR(40) NOT NULL,
Fecha_Nacimiento date,
RFC INT,
Centro_Tra VARCHAR(20) NOT NULL,
Puesto VARCHAR(20) NOT NULL,
Descrip_Puesto VARCHAR (20) NOT NULL,
Directivo BIT NOT NULL

);

INSERT INTO Empleados(Num_Empleado, Nombre, Apellido, Fecha_nacimiento, RFC, Centro_Tra, Puesto, Descrip_Puesto,Directivo) 
VALUES ('0101', 'Eduardo', 'Monroy Hernandez','2002/05/13','130502','cobranza','supervisor','supervisor cobranza','0')

INSERT INTO Empleados(Num_Empleado, Nombre, Apellido, Fecha_nacimiento, RFC, Centro_Tra, Puesto, Descrip_Puesto,Directivo) 
VALUES ('0102', 'Fernando', 'Moreno Garcia','2001/06/28','280601','cobranza','supervisor','supervisor cobranza','0'),
('0103', 'Fernando', 'Moreno Garcia','2001/06/28','280601','cobranza','supervisor','supervisor cobranza','0'),
('0104', 'Alicia', 'Romero Paredes','1978/11/16','161178','tienda','gerente','gerente banco','1'),
('0105', 'Maria Fernanda', 'Calderon Ruiz','2004/10/11','111004','cobranza','supervisor','supervisor cobranza','0'),
('0106', 'Eder Yahir', 'Segura Nieto','1988/01/29','290188','cobranza','gerente','gerente cobranza','1'),
('0107', 'Brandon', 'Carrillo Cruz','1999/12/09','091299','tienda','promotor','promotor banco','0'),
('0108', 'David', 'Escorza Avila','1975/06/11','110675','tienda','gerente','gerente cajas','1'),
('0109', 'Brenda', 'Perez Meneses','2002/05/15','150502','cobranza','supervisor','supervisor cobranza','0'),
('0110', 'Zamanta', 'Rizo Olivares','2000/02/24','240200','cobranza','supervisor','supervisor cobranza','0')
