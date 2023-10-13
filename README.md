[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XixB-tii)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=12361458)
# Proyecto Calificaciones colegio

# Análisis del problema

En este Programa se no solicito la creación de un colegio con tres tipos de sedes las cuales eran primaria, secundaria y preescolar, en donde este contara con alumnos, maestros y calificaciones.
Nosotros propusimos 5 clases en las cuales se realizó los siguiente:
La clase Sede tiene un atributo privado llamado nombre, un constructor que permite inicializar ese atributo cuando se crea una instancia de la clase y un método getNombre() que permite obtener el valor del atributo nombre. Esta clase se utiliza para representar sedes con nombres de primaria preescolar y secundaria.
La clase Alumno tiene cuatro atributos privados (sede, nivel, grado y grupo), un constructor para inicializar estos atributos y métodos públicos para obtener los valores de estos atributos. Esta clase se utiliza para representar a los alumnos en un sistema educativo.
La clase Maestro tiene varios atributos privados, un constructor para inicializar estos atributos y métodos públicos para obtener los valores de estos atributos. Esta clase se utiliza para representar a los maestros en un sistema educativo y gestionar información relacionada con ellos, como las sedes en las que enseñan, las asignaturas que imparten y los grupos a los que están asignados.
La clase Calificación tiene cuatro atributos privados para representar la materia, la asistencia, el cumplimiento del uniforme y la calificación numérica. Un constructor permite inicializar estos atributos y métodos públicos permiten obtener los valores de estos atributos. Esta clase se utiliza para representar las calificaciones de un estudiante en una materia específica.
La clase colegio crea objetos de diferentes clases relacionadas con un colegio (sedes, alumnos, calificaciones y maestros) y luego imprime información sobre estos objetos en la consola.

# Diagramas UML


La clase Colegio es la clase principal con un método main.
Las clases Alumno, Maestro y Calificación se representan como clases independientes.
La clase Alumno tiene una relación de composición con la clase Sede, lo que significa que un Alumno tiene una Sede. Además, tiene atributos como nivel, grado y grupo.
La clase Maestro tiene una relación de composición con la clase Sede, una relación de composición con la clase Alumno (para representar la lista de alumnos que tiene a cargo) y atributos como nombre, gruposAsignados y asignatura.
La clase Calificación tiene atributos como materia, asistencia, cumplimientoUniforme y calificación.



![Imagen proyecto](https://github.com/AGN-Teaching/proyecto-equipo-5/assets/141947952/b2a87387-6be4-441e-991d-2cb5ad778e6c)

# Diagrama UML de la clase Alumno.


Los atributos privados sede, nivel, grado y grupo se representan en la sección superior del rectángulo con un signo menos (-) delante de ellos, lo que indica que son atributos privados.
El constructor Alumno se representa con el símbolo +, que indica que es un constructor público.
Los métodos públicos getSede(), getNivel(), getGrado(), y getGrupo() se representan también con el símbolo +, indicando que son públicos.


![image](https://github.com/AGN-Teaching/proyecto-equipo-5/assets/141947952/bc343782-8450-4a5c-9e48-3a78eda1cdee)

# Diagrama UML de la clase Maestro.

Los atributos privados nombre, sedes, gruposAsignados, asignatura y alumnosPorGrupo se representan en la sección superior del rectángulo con un signo menos (-) delante de ellos, lo que indica que son atributos privados.
El constructor Maestro se representa con el símbolo +, que indica que es un constructor público.
Los métodos públicos getNombre(), getSedes(), getGruposAsignados(), getAsignatura() y getAlumnosPorGrupo() se representan también con el símbolo +, indicando que son públicos.



![image](https://github.com/AGN-Teaching/proyecto-equipo-5/assets/141947952/d66aad2e-b92f-46b5-ba53-c4d46d74fc4d)


#Diagrama UML de la clase Calificación.


Los atributos privados materia, asistencia, cumplimientoUniforme y calificación se representan en la sección superior del rectángulo con un signo menos (-) delante de ellos, lo que indica que son atributos privados.
El constructor Calificación se representa con el símbolo +, que indica que es un constructor público.
Los métodos públicos getMateria(), getAsistencia(), getCumplimientoUniforme() y getCalificacion() se representan también con el símbolo +, indicando que son públicos.


![image](https://github.com/AGN-Teaching/proyecto-equipo-5/assets/141947952/f0c43b66-accd-4036-b121-f6f894b71203)

# Diagrama UML de la clase Sede.


El atributo privado nombre se representa en la sección superior del rectángulo con un signo menos (-) delante de él, lo que indica que es un atributo privado.
El constructor Sede se representa con el símbolo +, que indica que es un constructor público.
El método público getNombre() se representa también con el símbolo +, indicando que es público.

![image](https://github.com/AGN-Teaching/proyecto-equipo-5/assets/141947952/47757db5-51f8-40de-98bf-668bf83370f6)




