# TPB708 Programación de aplicaciones en sistemas de información geográfica
## Tarea 02

### Fecha de entrega y entregables
La fecha límite de entrega es el **jueves 3 de setiembre de 2020**. Envíe al profesor por correo electrónico el archivo con el programa en Python resultante (ej. imc.py). Debe enviar un programa Python que pueda ejecutarse desde la línea de comandos (i.e. un archivo con extensión .py) y no un *notebook*.

### Desarrollo
En esta tarea, desarrollará un programa en Python que calculará el índice de masa corporal (IMC) de una persona, con base en los datos de su estatura y peso, los cuales serán provistos por el usuario a través del teclado y la pantalla. El programa verificará la calidad de los datos, calculará el IMC y le comunicará al usuario su valor y, además, si es considerado bajo, medio o alto.

Para calcular el IMC y determinar si es bajo, normal o alto, debe programar dos funciones:
- ```imc()```: recibe como argumentos el peso (en kilogramos, por ejemplo 70) y la estatura (en metros, por ejemplo 1.75) de una persona. Retorna el valor del IMC con base en el cáculo especificado en [https://www.diabetes.ca/diabetes-and-you/healthy-living-resources/weight-management/body-mass-index-bmi-calculator](https://www.diabetes.ca/diabetes-and-you/healthy-living-resources/weight-management/body-mass-index-bmi-calculator). 
- ```interpretacion_imc()```: recibe como argumento el IMC de una persona. Retorna una hilera de texto con el valor:
    - "Bajo" si menor que 18.5).
    - "Normal" si es mayor o igual a 18.5 y menor que 25.
    - "Alto" si es mayor o igual que 25.

### Calificación
