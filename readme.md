Calculadora de Huella de Carbono

La Calculadora de Huella de Carbono es una aplicación desarrollada para ayudar a las personas a comprender cómo sus hábitos diarios afectan al medio ambiente.

Muchas personas contribuyen al cambio climático sin conocer el impacto de sus acciones cotidianas. Esto dificulta que adopten hábitos más sostenibles.

La aplicación realizará preguntas sobre transporte, consumo de energía y reciclaje. Con esta información calculará una huella de carbono estimada y ofrecerá recomendaciones personalizadas para reducir el impacto ambiental.

# Funciones principales

* Registro de hábitos diarios.
* Cálculo aproximado de la huella de carbono.
* Clasificación del impacto ambiental.
* Recomendaciones para mejorar los hábitos ecológicos.



Ayudar a los usuarios a tomar decisiones más sostenibles y generar conciencia sobre el cambio climático mediante información sencilla y fácil de entender.

Las bibliotecas que voy a utilizar:
colorama (para mejorar la interfaz de texto en la consola)
json (para guardar resultados e historial)
datetime (para registrar fechas de los cálculos)
pyttsx3 (para añadir síntesis de voz en versiones futuras)
Referencias útiles:
https://github.com
Plataforma para alojar y gestionar el proyecto.
https://www.python.org
Documentación oficial de Python.
https://github.com/topics/carbon-footprint
Ejemplos de proyectos relacionados con huella de carbono y sostenibilidad.
Los artículos de la guía que me ayudarán durante el desarrollo:
¿Qué es la huella de carbono?

https://www.nationalgeographicla.com/medio-ambiente/que-es-la-huella-de-carbono

Este artículo explica qué es la huella de carbono, cómo se genera y por qué es importante reducirla.

Cambio climático y sostenibilidad

https://www.un.org/es/climatechange

Información oficial de las Naciones Unidas sobre el cambio climático y sus efectos.

Documentación de pyttsx3

https://pyttsx3.readthedocs.io

Guía para implementar síntesis de voz en Python.

Documentación de JSON en Python

https://docs.python.org/3/library/json.html

Explica cómo guardar y cargar información utilizando archivos JSON.
-----------------------------------------------------------------

# Lista de Control de Pruebas - Calculadora de Huella de Carbono

## 1. Funcionalidad (Prioridad Alta)

### Prueba 1: Inicio del programa

* Verificar que el programa se ejecuta sin errores.
* Resultado esperado: La aplicación muestra la pantalla de bienvenida.

### Prueba 2: Entrada de datos

* Verificar que el usuario puede ingresar todos los datos solicitados.
* Resultado esperado: El programa acepta los valores correctamente.

### Prueba 3: Cálculo de la huella de carbono

* Verificar que el cálculo se realiza correctamente.
* Resultado esperado: Se muestra una puntuación de huella de carbono basada en las respuestas del usuario.

### Prueba 4: Recomendaciones ambientales

* Verificar que el programa muestra recomendaciones según el resultado obtenido.
* Resultado esperado: El usuario recibe consejos adecuados para reducir su impacto ambiental.

## 2. Interfaz de Usuario (Prioridad Media)

### Prueba 5: Claridad de los mensajes

* Verificar que todas las instrucciones sean fáciles de entender.
* Resultado esperado: El usuario comprende cómo utilizar la aplicación sin ayuda adicional.

### Prueba 6: Formato de salida

* Verificar que los resultados se muestran de forma organizada.
* Resultado esperado: La información aparece correctamente estructurada en pantalla.

## 3. Validación de Datos (Prioridad Alta)

### Prueba 7: Valores inválidos

* Introducir letras donde se esperan números.
* Resultado esperado: El programa muestra un mensaje de error y solicita nuevamente el dato.

### Prueba 8: Valores negativos

* Introducir números negativos.
* Resultado esperado: El programa rechaza los valores inválidos.

## 4. Rendimiento (Prioridad Baja)

### Prueba 9: Tiempo de respuesta

* Verificar que el cálculo se realiza rápidamente.
* Resultado esperado: El resultado aparece en menos de 2 segundos.

## 5. Funciones Futuras (Prioridad Baja)

### Prueba 10: Síntesis de voz

* Verificar que la voz reproduce correctamente los resultados.
* Resultado esperado: El usuario escucha el resultado sin errores de audio.

## Resultado esperado del proyecto

* El programa debe ejecutarse sin errores.
* Debe calcular correctamente la huella de carbono.
* Debe proporcionar recomendaciones ambientales útiles.
* Debe ser fácil de utilizar para cualquier usuario.

