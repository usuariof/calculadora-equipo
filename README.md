# calculadora-equipo
## Tabla de Integrantes
| Lider | Fidel Cortes |
| Estudiante A | Fidel Cortes |
| Estudiante B | Mateo Mojica |
| Estudiante c | Facundo Mendoza |
- ## Instalacion
- Ejecutar:
python calculadore.py
## Estado
Proyecto en desarrollo
## Funciones Disponibles 
1. Suma
2. Resta
3. Multiplicacion
4. Division
## Ejemplos de Uso
- La calculadora se ejecuta desde la terminal o consola de comandos utilizando Python
- Ejemplo: python calculadora.py
## Notas del Desarrollador
Este proyecto fue desarrollado bajo un entorno de simulación de trabajo colaborativo utilizando Git y GitHub. A continuación se detallan los aspectos técnicos clave del proceso de desarrollo:

###  Flujo de Trabajo 
Para garantizar la integridad del código y permitir el desarrollo en paralelo, aplicamos el flujo de trabajo basado en ramas (Feature Branch Workflow):
1. **Rama Principal (`main`):** Actúa como la línea de producción estable y solo contiene código completamente revisado y funcional.
2. **Ramas de Funcionalidad:** Cada desarrollador trabajó de forma aislada en su propia rama antes de unificar el proyecto[cite: 2, 7]:
   * `A/sumas-restas` para las mejoras del núcleo aritmético básico.
   * `B/multi-division` para la lógica avanzada y validaciones.
   * `C/documentacion` para la redacción de este archivo y control de calidad.

### ⚠️ Consideraciones Técnicas del Código
* **Validación Crítica:** Se puso especial énfasis en la robustez de la función de división. El sistema cuenta con un bloque de validación condicional que intercepta los intentos de división por cero antes de que Python genere un error de ejecución (`ZeroDivisionError`), devolviendo en su lugar un mensaje controlado de advertencia.
* **Persistencia del Historial:** Siguiendo las buenas prácticas de Git, una vez que las ramas locales cumplieron su ciclo de vida y fueron fusionadas en GitHub, se procedió a la limpieza del repositorio eliminando las ramas remotas y locales para mantener un historial limpio y legible.
