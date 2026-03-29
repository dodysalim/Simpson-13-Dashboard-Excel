# 📊 Dashboard de Integración Numérica Simpson 1/3 (Excel VBA)

Una herramienta avanzada y de alto rendimiento desarrollada en Excel para calcular integrales definidas utilizando la **Regla de Simpson 1/3**, con una interfaz de usuario moderna inspirada en el estilo "GitHub Dark".

## ✨ Características Principales
- **Interfaz Inmersiva**: Modo de visualización completa que oculta encabezados de Excel, líneas de cuadrícula y celdas no utilizadas para un efecto de software independiente.
- **Gráficos Dinámicos**: Renderizado automatizado de un "Gráfico Combinado" que muestra el área bajo la curva con transparencias personalizadas y una línea de función nítida.
- **Motor Matemático Robusto**: Evaluación en tiempo real de funciones algebraicas complejas (ej. `x^3`, `sin(x)`, `exp(x)`) a prueba de configuraciones regionales (punto/coma decimal).
- **Tabla de Datos Profesional**: Formato limpio con identificación de paridad (intervalos pares e impares) para transparencia en el cálculo.

## 🚀 Cómo usarlo
1. Descarga el archivo `.xlsm` (o copia el código de la carpeta `src`).
2. Habilita las Macros en Excel.
3. Ejecuta la macro `Simpson_Dashboard_Pro`.
4. Ingresa tus límites (a, b), el número de intervalos (n) y la función f(x).

## 🤓 El "Dato Curioso" Matemático
Durante las pruebas de estrés, evaluar la función **f(x) = x³** con límites de **-100 a 100** arroja exactamente **0.000000**. Esto demuestra la precisión del algoritmo al respetar la simetría matemática, donde las áreas negativas y positivas se cancelan mutuamente.