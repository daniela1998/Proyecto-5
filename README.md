# Proyecto-5

# Integrantes:
- Estudiante: **Melissa Rodríguez Murillo**
- Carné: **B76529**
- Grupo: **1**

- Estudiante: **Daniela Ríos Mora**
- Carné: **B65854**
- Grupo: 1

- Estudiante: **Dariana Detrinidad Lorenzana** 
- Carné: **B82576**
- Grupo: **1**


# Resumen 
El presente proyecto consiste en analizar los procesos M/M/s. eL caso especial de los procesos aleatorios donde existen "estados" y "transiciones" entre estos estados, las cadenas de Markov modelan las probabilidades de transición y el tiempo de permanencia entre cada estado. En particular, la teoría de colas describe la evolución del número de elementos en la fila, dado un flujo de entrada y un flujo de salida.

# Asignaciones
El proyecto se basa en conocer el número de servidores necesarios para un proceso de vacunación de manera que el sistema no exceda las 100 personas en la fila el 95% del tiempo de servicio.
Cuenta con dos partes :
- Determinación teórica del número s de servidores necesarios
- Simulación de los resultados te´roticos obtenidos

# Resultados
### Primera simulación:

![image](https://user-images.githubusercontent.com/22760012/127784387-fd52bcfc-0ce1-4cc3-bd2b-72dea0c06321.png)

De los resultados obtenidos en la simulación con $\nu = 7.25$ como total de servicios por minuto para 29 servidores donde cada uno atiende a 0.25 personas por minuto, en un tiempo de alredor 8 horas, con un número de clientes atendidos en total de 3155, la fila nunca llegan a exceder las 100 personas por más del 5% de las horas, en varias pruebas hechas a la simulación se mantenia en solicitudes en fila de 0%, lo que signoifica que nunca se acumulaban 100 personas en la fila, sin embargo, en algunas pruebas si llegaba a subir, pero nunca superaba el 5%, por lo que podemos saber que si se cumple con las especificaciones teniendo 29 "servidores" para el proceso de vacunación. 

### Segunda Simulación:

![image](https://user-images.githubusercontent.com/22760012/127784429-27d323a2-6160-448d-9aea-2d8583f362e5.png)

Para la segunda prueba con un servidor menos, o sea $s=28$, por lo que $\nu=7$, atendiendo cada 0.25 personas por minuto, para varias pruebas realizadas se obtienen resultados muy distintos puede tanto cumplir o no con los requerimientos pues a veces se acumulaban en la fila más de 100 perosonas por un tiempo mayor a 5%, o también no se llegaba a exceder las 100 personas en la fila, sin embargo, tomaba un tiempo mucho mayor atender a los clientes, para un número de personas igual a la prueba anterior 3155, por lo que no siempre llega a cumplir con las especificaciones.

### Tercera Simulación:

![image](https://user-images.githubusercontent.com/22760012/127784439-24a58ac5-5681-40b0-b01b-b70d59285923.png)

Para la última simulación realizada, con varios menos de servidores, para un $\nu=6$, lo que significa que hay 24 servidores que atienden a 0.25 personas por minuto, los requerimientos nunca se llegaron a cumplir, el tiempo de antención a todas las personas (3155) fue muy superior a las 8 horas por lo que se atenderían a menos clientes para cumplir con su jornada, y la fila, en todas las pruebas realizadas, acumulo a las 100% por más de 5% del tiempo, concluyendo así que nunca se cumple con las especificaciones requeridas y para solventar de manera eficiente lo requerido se debe contar con 29 servidores.




