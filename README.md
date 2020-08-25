# TPB708 Programación de aplicaciones en sistemas de información geográfica
## Tarea 02

### Fecha de entrega y entregables
La fecha límite de entrega es el **jueves 3 de setiembre de 2020**.

Debe enviarle al profesor por correo electrónico el archivo con el programa en Python resultante (ej. imc.py). **Debe enviar un programa Python que pueda ejecutarse desde la línea de comandos del sistema operativo (i.e. un archivo con extensión .py) y no un *notebook*.**

### Desarrollo
En esta tarea, desarrollará un programa en Python que calculará el índice de masa corporal (IMC) de una persona, con base en los datos de su estatura y peso, los cuales serán provistos por el usuario a través del teclado y la pantalla. El programa verificará la calidad de los datos, calculará el IMC y le comunicará al usuario su valor y, además, si es considerado bajo, medio o alto.

El programa debe verificar que tanto el peso como la estatura sean mayores que cero y solicitarle de nuevo estos valores al usuario si no se cumple esta condición, hasta que proporcione un valor válido. Si el usuario ingresa un valor que no puede tratarse como un número

Para calcular el IMC y determinar si es bajo, normal o alto, debe programar dos funciones:
- ```imc()```
    - Recibe como argumentos dos números decimales correspondientes al peso (en kilogramos, por ejemplo 70.5) y a la estatura (en metros, por ejemplo 1.75) de una persona.
    - Retorna un número decimal correspondiente al valor del IMC, con base en el cáculo especificado en [https://www.diabetes.ca/diabetes-and-you/healthy-living-resources/weight-management/body-mass-index-bmi-calculator](https://www.diabetes.ca/diabetes-and-you/healthy-living-resources/weight-management/body-mass-index-bmi-calculator). 
- ```interpretacion_imc()```:
    - Recibe como argumento un número decimal correspondiente al IMC de una persona.
    - Retorna una hilera de texto con el valor:
        - "Bajo" si menor que 18.5.
        - "Normal" si es mayor o igual a 18.5 y menor que 25.
        - "Alto" si es mayor o igual que 25.

### Calificación
1 (25%). Implementación de la funcion ```imc()```.
2 (25%). Implementación de la función ```interpretacion_imc()```.
3 
