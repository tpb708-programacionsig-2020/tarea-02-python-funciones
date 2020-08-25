# TPB708 Programación de aplicaciones en sistemas de información geográfica
## Tarea 02

### Fecha de entrega y entregables
La fecha límite de entrega es el **jueves 3 de setiembre de 2020, antes de las 5:00 p.m.**.

Debe enviarle al profesor por correo electrónico el archivo con el programa en Python resultante (ej. ```imc.py```). **Debe ser un programa que pueda ejecutarse desde la línea de comandos del sistema operativo (i.e. un archivo con extensión .py), no un *notebook* de Jupyter.**

**ESTA TAREA ES PARA REALIZARSE EN FORMA INDIVIDUAL**.

### Objetivos
Aplicar varios conceptos de programación en Python cubiertos en clase, como variables, condicionales, ciclos y funciones, entre otros.

### Desarrollo
Debe implementar un programa en Python para calcular el índice de masa corporal (IMC) de una persona, con base en los datos de su estatura y peso, los cuales serán provistos por el usuario a través del teclado y la pantalla. El programa debe verificar la calidad de los datos, calcular el IMC y comunicarle al usuario su valor y, además, si es considerado bajo, medio o alto.

El programa debe verificar que tanto el peso como la estatura sean mayores que cero y solicitarle de nuevo estos valores al usuario si no se cumple esta condición, hasta que proporcione un valor válido. Si el usuario ingresa un valor que no puede tratarse como un número decimal, el programa debe alertar al usuario de esta situación y finalizar.

Para calcular el IMC y determinar si es bajo, normal o alto, debe programar dos funciones a las cuales llamará desde el cuerpo principal del programa:
- ```calcular_imc()```
    - Recibe como argumentos dos números decimales correspondientes al peso (en kilogramos, por ejemplo 70.5) y a la estatura (en metros, por ejemplo 1.75) de una persona.
    - Retorna un número decimal correspondiente al valor del IMC, con base en el cáculo especificado en [https://www.diabetes.ca/diabetes-and-you/healthy-living-resources/weight-management/body-mass-index-bmi-calculator](https://www.diabetes.ca/diabetes-and-you/healthy-living-resources/weight-management/body-mass-index-bmi-calculator). 
- ```interpretar_imc()```:
    - Recibe como argumento un número decimal correspondiente al IMC de una persona.
    - Retorna una hilera de texto con el valor:
        - "Bajo" si el IMC menor que 18.5.
        - "Normal" si el IMC es mayor o igual a 18.5 y menor que 25.
        - "Alto" si el IMC es mayor o igual que 25.

### Calificación
**Entrada**  
1 (10%). Lectura de los valores de estatura y peso.  
2 (15%). Verificación de que los valores de peso y estatura sean mayores que cero.  
3 (15%). Verificación de que los valores de peso y estatura puedan ser manejados como números decimales.  

**Procesamiento**  
4 (25%). Implementación y llamado de la funcion ```calcular_imc()```.  
5 (25%). Implementación y llamado de la función ```interpretar_imc()```.

**Salida**  
6 (10%). Impresión del valor del IMC y si es considerado bajo, normal o alto.
