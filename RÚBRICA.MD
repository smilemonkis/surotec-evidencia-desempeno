# Rúbrica de Evaluación - Taller de Lógica de Programación y Git

## Distribución de la Evaluación

| Criterio | Peso | Nota Máxima |
|----------|------|-------------|
| Funcionalidad de los Ejercicios | 40% | 2.0 |
| Flujo de Trabajo con Git | 25% | 1.25 |
| Calidad del Código | 20% | 1.0 |
| Sistema de Menú | 15% | 0.75 |
| **TOTAL** | **100%** | **5.0** |

## 1. Funcionalidad de los Ejercicios (40% - 2.0 puntos)

| Aspecto | Descripción | Puntos |
|---------|-------------|--------|
| Ejercicios Correctos | Cada ejercicio funcional y que cumple con los requerimientos | 0.09 por ejercicio (20 ejercicios) |
| Uso de Funciones | Todos los ejercicios implementados mediante funciones | 0.10 |
| Parámetros y Return | Correcta recepción de datos por parámetros y devolución mediante return | 0.10 |

### Desglose por Ejercicio

Cada ejercicio vale 0.09 puntos y se evalúa así:

- Resuelve correctamente el problema planteado
- Maneja correctamente los casos edge y validaciones solicitadas
- Retorna el tipo de dato especificado en el enunciado
- La lógica implementada es correcta y eficiente

## 2. Flujo de Trabajo con Git (25% - 1.25 puntos)

| Aspecto | Descripción | Puntos |
|---------|-------------|--------|
| Estructura de Carpetas | Carpeta con nombre completo separado por guiones creada correctamente | 0.10 |
| Archivos Individuales | 20 archivos JavaScript individuales con nomenclatura correcta | 0.20 |
| Archivo menu.js | Archivo del menú con el nombre exacto en la ubicación correcta | 0.05 |
| Commit Inicial | Commit de setup con mensaje correcto | 0.10 |
| Un Commit por Ejercicio | Exactamente un commit por cada ejercicio resuelto | 0.45 |
| Mensajes de Commit | Mensajes claros, técnicos y específicos en todos los commits | 0.25 |
| Pull Request | PR creado únicamente al finalizar los 20 ejercicios y el menú | 0.10 |

### Criterios de Penalización en Git

- Múltiples ejercicios en un solo commit: -0.05 por cada violación
- Mensajes genéricos o no técnicos: -0.02 por cada mensaje inadecuado
- Push antes de completar todos los ejercicios: -0.20
- Historial de commits desordenado o con correcciones excesivas: -0.10
- Archivos con nombres incorrectos: -0.02 por archivo
- Todos los ejercicios en un solo archivo: -0.50

## 3. Calidad del Código (20% - 1.0 puntos)

| Aspecto | Descripción | Puntos |
|---------|-------------|--------|
| Nomenclatura camelCase | Todas las variables y funciones en camelCase | 0.25 |
| Ausencia de Comentarios | El código no contiene comentarios | 0.20 |
| Sintaxis Correcta | Sin errores de sintaxis en ningún ejercicio | 0.25 |
| Claridad y Legibilidad | Código limpio, indentación correcta y nombres descriptivos | 0.15 |
| Eficiencia | Soluciones optimizadas sin lógica redundante | 0.15 |

### Criterios de Penalización en Calidad

- Uso de snake_case, PascalCase o cualquier otra convención diferente a camelCase: -0.02 por variable
- Presencia de comentarios en el código: -0.02 por comentario
- Errores de sintaxis que impidan la ejecución: -0.05 por error
- Código desorganizado o difícil de leer: -0.03 por función
- Lógica innecesariamente compleja: -0.02 por ejercicio

## 4. Sistema de Menú (15% - 0.75 puntos)

| Aspecto | Descripción | Puntos |
|---------|-------------|--------|
| Menú Funcional | El menú se ejecuta y muestra todas las opciones correctamente | 0.15 |
| Navegación Correcta | Permite acceder a todos los ejercicios desde el menú | 0.15 |
| Ejecución Continua | El menú se mantiene activo hasta seleccionar salir | 0.15 |
| Integración con Ejercicios | Ejecuta correctamente las funciones de cada ejercicio | 0.15 |
| Manejo de Errores | Valida opciones inválidas y muestra mensajes apropiados | 0.10 |
| Retorno al Menú | Después de ejecutar un ejercicio vuelve al menú principal | 0.05 |

### Criterios de Penalización en Menú

- Menú no funcional o con errores críticos: -0.30
- No permite salir correctamente: -0.10
- No retorna al menú después de ejecutar ejercicio: -0.05
- Opciones inválidas no manejadas: -0.05
- No muestra todos los ejercicios: -0.10

## Escala de Calificación Final

| Rango | Calificación |
|-------|--------------|
| 4.5 - 5.0 | Excelente |
| 4.0 - 4.4 | Sobresaliente |
| 3.5 - 3.9 | Aceptable |
| 3.0 - 3.4 | Suficiente |
| 0.0 - 2.9 | Insuficiente |

## Requisitos Mínimos para Aprobar

Para obtener una calificación aprobatoria se debe cumplir con:

- Mínimo 15 ejercicios completamente funcionales
- Cada ejercicio en su archivo JavaScript individual correspondiente
- Sistema de menú funcional que permita acceder a todos los ejercicios
- Historial de Git con commits individuales por ejercicio
- Ausencia total de comentarios en el código
- Uso exclusivo de camelCase en nomenclatura
- Estructura de carpetas y archivos correcta

## Causales de Calificación de 0.0

- Plagio detectado de otro estudiante o fuente externa
- No realizar fork del repositorio
- No crear Pull Request al repositorio original
- Entrega fuera del plazo establecido
- Código que no ejecuta por errores críticos de sintaxis en más del 50% de los ejercicios
- Todos los ejercicios en un solo archivo en lugar de archivos individuales
- Ausencia del sistema de menú