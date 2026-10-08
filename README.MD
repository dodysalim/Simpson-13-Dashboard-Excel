![Simpson 1/3](docs/cover.svg)

# Simpson 1/3

**Aproximación de integrales con tabla de puntos y visualización del método.**

PERSONAL · CÁLCULO Y EXCEL VBA · Excel · VBA · Integración numérica

[Portafolio](https://dodysalim.github.io/) · [Caso y alcance](docs/PORTFOLIO_CASE.md) · [Verificación](docs/VALIDATION.md)

## La pregunta

¿Cómo calcular una integral definida y mostrar los pesos pares e impares de Simpson 1/3?

## Qué puedes revisar

- Libro Excel con dashboard, entradas y gráfica.
- Código VBA separado para revisar e importar.
- Validación de n par y restauración de pantalla ante errores.

## Inicio local

Abre `Simpson_Pro.xlsm` en Excel de escritorio. Para usar la fuente revisada, importa `Simpson_VBA.txt` en un módulo VBA y ejecuta `Simpson_Dashboard_Pro`. Conserva una copia del libro antes de sustituir el módulo.

## Datos y configuración

Requiere Excel de escritorio y macros habilitadas. El código fuente actualizado debe importarse en el editor VBA; no se reemplazó el binario VBA del XLSM.

## Recorrido por el código

| Ruta | Qué contiene |
| --- | --- |
| [Simpson_Pro.xlsm](Simpson_Pro.xlsm) | Libro original |
| [Simpson_VBA.txt](Simpson_VBA.txt) | Fuente VBA revisada |

## Comprobación y alcance

Fuente revisada: fRow usa Long y ScreenUpdating se restaura ante un error. La macro y el archivo XLSM no se ejecutaron en Excel durante esta revisión.

n debe ser par, entre 2 y 100.000. La precisión depende de la función y del paso. No se promete exactitud para cualquier función.

## Autoría

Proyecto personal. Dody Salim Dueñas Remache.

[Documentación anterior](docs/ORIGINAL_README.md), conservada como referencia histórica.
