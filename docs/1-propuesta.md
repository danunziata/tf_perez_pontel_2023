# Prupuesta  

## Trabajo Final Aplicaciones TCP/IP

## Integrantes:

- Daniela Pontel
- M. Sol Perez

## [Iluminacion inteligente en Universidades]

### Resumen:
La propuesta tiene como objetivo optimizar la gestión de consumo energético dentro de las aulas pertenecientes a una Universidad  y/o escuelas. Esto  mediante la implementación de un sistema de gestión de control de iluminación inteligente que se tiene como premisa realizar el control del nivel de luz solar que ingresa al aula y si hay personas en la misma o no, para con esa información tomar medidas del nivel de luz artificial que debe haber dentro del espacio. Esto se busca hacer en  tiempo real para mejorar la eficiencia energética de la institución.
Para abordar este problema, se propone utilizar un Arduino 1 y sensores: infrarrojo y de fotoresistencia junto con actuadores de encendido y apagado. Estos dispositivos permitirán recopilar datos sobre el nivel de luz y ocupación y tomar acciones automatizadas para regular la luz artificial de manera eficiente. Al no contar con los mismos físicamente se va a llevar a cabo la virtualización de los mismos en programa autodesk Tinkercad. Se envía mediante WiFi la información hacia la aplicación de manejo de IoT, Thingsboard, que permite manejar la información y utilizar paneles para mostrar la información estadística que se desee mostrar con las opciones que la plataforma permite.

### Objetivos
#### Objetivos generales:
- Reducir el consumo de energía innecesario dentro de las aulas
- Mejorar la eficiencia energética regulando el nivel de luz dentro del día y dandole mas vida util a los focos
- Tener un mayor control sobre el gasto energético e información sobre el consumo para una óptima administración

#### Objetivos específicos:
- Monitoreo continuo y en tiempo real: El sistema permitirá el monitoreo constante del nivel de luz y ocupación dentro de las aulas.
- Control automático y ajuste de los focos: Se implementarán actuadores que permitirán el control automatizado de los sistemas de encendido o apagado y nitidez en función de los datos recopilados. Esto asegurará un ajuste preciso de la luz en base a las condiciones de luz naturales optimizando el consumo energético.
- Análisis y optimización de datos: Se llevará a cabo un análisis detallado de los datos recopilados, identificando patrones y tendencias. Esto permitirá mejorar aún más el sistema de gestión de luminosidad  ajustando los umbrales de luz, identificando las aulas se mayor y menor uso  y optimizando los recursos utilizados para el control del nivel de luz.

### Plan de Trabajo Tentativo

- **Fase 1:** Análisis y diseño de la aplicación.
Realizar un análisis sobre la medición de la luz solar y la detección de humanos en una habitación.
Considerar el hardware para la implementación, sensores etc.
Establecer las posibles tecnologías para llevar a cabo el proyecto y los protocolos que las mismas implementan.

- **Fase 2:** Desarrollo de la aplicacion
Desarrollar el código para adquirir los datos de los sensores de luz e infrarrojo.
Implementar la lógica de control para regular el nivel de luz y el prendido y apagado.

- **Fase 3:** Dockerización de la aplicación
Crear contenedor Docker para la aplicación y sus dependencias. O una imagen docker, según como se considere necesario.
Realizar pruebas de funcionamiento en el entorno de contenedores.

- **Fase 4:** Despliegue de la aplicación en un clúster de Kubernetes.
Configurar un clúster de Kubernetes y los recursos necesarios para el despliegue usando Minicube.
Desplegar la aplicación en el clúster y realizar pruebas de escalabilidad y disponibilidad.
Configurar políticas de monitoreo y gestión de recursos en el clúster.

- **Fase 5:** Configuración del sistema de monitoreo en el clúster.
Configurar la herramienta de monitoreo y almacenamiento Things Board para recopilar y visualizar los datos de temperatura en tiempo real.
Diseñar paneles de control personalizados para visualizar los datos y establecer alertas.
Generar informes periódicos sobre el rendimiento y la eficiencia energética del sistema.

- **Fase 6:** Realización de pruebas.
Realizar pruebas exhaustivas para verificar el correcto funcionamiento del sistema en diferentes aulas.
Actualizar los niveles de umbrales e ir sistematizando aún más la aplicación según los resultados obtenidos.
Evaluar el rendimiento de la comunicación inalámbrica y el comportamiento a largo plazo de la herramienta Thingsboard.

- **Fase 7:** Ajustes finales, corrección de errores y entrega del proyecto.
Realizar ajustes y mejoras basados en los resultados de las pruebas y la retroalimentación del cliente.
Documentar el sistema Iluminación Inteligente en Universidades, incluyendo instrucciones de instalación y configuración.
Preparar la documentación técnica final y entregar el proyecto completo al cliente.
