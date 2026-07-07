
CREATE TABLE lunes (
    id SERIAL PRIMARY KEY,
    actividad VARCHAR(150) NOT NULL
);

CREATE TABLE Martes (
    id SERIAL PRIMARY KEY,
    actividad VARCHAR(150) NOT NULL
);

CREATE TABLE Miercoles (
    id SERIAL PRIMARY KEY,
    actividad VARCHAR(150) NOT NULL
);

CREATE TABLE Jueves (
    id SERIAL PRIMARY KEY,
    actividad VARCHAR(150) NOT NULL,
    observacion VARCHAR(250)
);

INSERT INTO Lunes (actividad) VALUES 
('Salir al Institulo')

INSERT INTO martes (actividad) VALUES 
('Estudiar Base de datos');

INSERT INTO miercoles (actividad) VALUES 
('Estudiar para la exposicion');

INSERT INTO jueves (actividad, observacion) VALUES 
('Estudiar para el examen', 'Dar el Examen');

