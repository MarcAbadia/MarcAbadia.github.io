# Gestión de Memoria
## Introducción
La gestión de memoria en sistemas operativos es crucial para optimizar el uso de los recursos de hardware y garantizar que los programas se ejecuten de manera eficiente. Aquí se exploran los aspectos clave relacionados con la gestión de memoria:
## 6.1 Descripción en Sistemas Operativos
### Espacio de Direcciones: 
Cada proceso tiene su propio espacio de direcciones, que va desde la dirección 0 hasta la máxima dirección de memoria permitida para ese proceso.
### Segmentación:
Divide el espacio de direcciones en segmentos lógicos, como código, datos y pila.
### Paginación:
Divide la memoria física y virtual en páginas, permitiendo una gestión más eficiente de los recursos.
### Segmentación Paginada: 
Combina segmentación y paginación para proporcionar flexibilidad y eficiencia.
## 6.2 Tipos de Asignación de Memoria
### Asignación Estática:
La memoria se asigna durante la compilación o la carga del programa y no cambia durante la ejecución.
### Asignación Dinámica: 
La memoria se asigna y libera durante la ejecución del programa. Facilita la gestión eficiente de la memoria, pero requiere cuidado para evitar fugas de memoria.
## 6.3 Estrategias de Gestión (Paginación, Segmentación)
### Paginación: 
 Divide la memoria en bloques fijos (páginas) y asigna estas páginas a ubicaciones físicas. Facilita la gestión de la memoria, pero puede generar fragmentación interna.
 ### Segmentación: 
 Divide el espacio de direcciones en segmentos lógicos que pueden crecer o decrecer dinámicamente. Proporciona flexibilidad, pero puede generar fragmentación externa.
### Paginación Segmentada:
Combina las ventajas de la paginación y la segmentación para abordar las limitaciones de cada enfoque.

La gestión de memoria es esencial para evitar conflictos entre procesos y garantizar que cada uno tenga acceso a la cantidad necesaria de recursos. En los próximos apartados, se explorarán las estrategias de monitoreo y optimización de procesos, así como la importancia de la retroalimentación continua en la mejora de la gestión de procesos.