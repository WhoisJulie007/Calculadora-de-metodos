# Calculadora de Métodos Numéricos

Una aplicación web interactiva para resolver problemas de métodos numéricos. Incluye implementaciones completas de interpolación, regresión, búsqueda de raíces, sistemas de ecuaciones no lineales, integración numérica y más.

## 🚀 Características

### Parcial 1 - Interpolación, Regresión y Raíces

#### Interpolación
- **Interpolación Simple (Lineal)**: Interpolación lineal entre dos puntos
- **Interpolación Cuadrática (Newton)**: Interpolación usando la forma de Newton para 3 puntos
- **Lagrange Lineal**: Polinomio de Lagrange de grado 1
- **Lagrange Cuadrática**: Polinomio de Lagrange de grado 2
- **Newton - Diferencias Divididas**: Polinomio de Newton con tabla de diferencias divididas (grado 1-5)

#### Regresión y Raíces
- **Mínimos Cuadrados**: Regresión lineal y cuadrática con cálculo de R²
- **Raíces: Newton-Raphson**: Método iterativo para encontrar raíces de ecuaciones
- **Raíces: Secantes**: Método de la secante para encontrar raíces

### Parcial 2 - Sistemas No Lineales

- **Sistemas No Lineales: Punto Fijo**: Método de punto fijo con criterio de convergencia
- **Sistemas No Lineales: Newton-Raphson**: Método de Newton-Raphson para sistemas con matriz Jacobiana

### Ordinario - Métodos Adicionales

- **Interpolación Mínimos Cuadrados**: Reutiliza el método de mínimos cuadrados
- **Newton Raphson Solución de Ecuaciones**: Reutiliza el método de Newton-Raphson
- **Integración Numérica Método de Simpson**: Regla de Simpson 1/3 (un intervalo y múltiples intervalos)
- **Integración Numérica Método del Trapecio**: Regla del trapecio (un intervalo y múltiples intervalos)
- **Sistemas de Ecuaciones Lineales con Determinante**: Resolución usando matriz inversa y determinante

## 📋 Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para cargar las librerías externas)

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura de la aplicación
- **CSS3**: Estilos y diseño responsive
- **JavaScript (Vanilla)**: Lógica de la aplicación
- **Math.js**: Librería para cálculos matemáticos y manipulación de expresiones
- **Chart.js**: Visualización de gráficas para interpolación y regresión

## 📦 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/ordimetodos.git
cd ordimetodos
```

2. Abre el archivo `OrdinarioMetodosNumericos.html` en tu navegador:
```bash
# En macOS/Linux
open OrdinarioMetodosNumericos.html

# En Windows
start OrdinarioMetodosNumericos.html
```

O simplemente arrastra el archivo HTML a tu navegador.

## 💻 Uso

1. Abre `OrdinarioMetodosNumericos.html` en tu navegador
2. Selecciona el método numérico que deseas utilizar desde el menú principal
3. Ingresa los datos requeridos según el método seleccionado
4. Haz clic en "Calcular" para obtener los resultados
5. Revisa los pasos detallados y resultados mostrados

### Ejemplo: Método de Simpson

Para calcular la integral:
```
∫[-1 to 1] (1 / sqrt(2 * pi)) * exp(x^2 / 2) dx
```

1. Selecciona "Integración Numérica Método de Simpson"
2. Elige "Múltiples intervalos"
3. Ingresa:
   - Función: `(1 / sqrt(2 * pi)) * exp(x^2 / 2)`
   - a: `-1`
   - b: `1`
   - n: `6`
4. Haz clic en "Calcular"

## 📚 Métodos Implementados

### Interpolación
- Fórmulas de interpolación lineal, cuadrática y de orden superior
- Métodos de Lagrange y Newton
- Visualización gráfica de los polinomios interpolantes

### Regresión
- Regresión por mínimos cuadrados (lineal y cuadrática)
- Cálculo de coeficiente de determinación (R²)
- Visualización comparativa de ajustes

### Búsqueda de Raíces
- Método de Newton-Raphson con visualización gráfica
- Método de la secante
- Tablas de iteraciones con cálculo de errores

### Sistemas No Lineales
- Método de punto fijo con análisis de convergencia
- Método de Newton-Raphson para sistemas con matriz Jacobiana
- Soporte para sistemas de 2, 3 o 4 variables

### Integración Numérica
- Regla de Simpson 1/3 (un intervalo y múltiples intervalos)
- Regla del Trapecio (un intervalo y múltiples intervalos)
- Cálculo paso a paso con todos los puntos evaluados

### Sistemas Lineales
- Resolución mediante matriz inversa
- Cálculo de determinante
- Verificación de resultados

## 🎨 Características de la Interfaz

- **Diseño Responsive**: Funciona en dispositivos móviles y de escritorio
- **Interfaz Intuitiva**: Navegación clara y fácil de usar
- **Resultados Detallados**: Muestra todos los pasos del cálculo
- **Gráficas Interactivas**: Visualización de funciones y puntos
- **Validación de Entradas**: Verifica que los datos ingresados sean válidos
- **Normalización de Funciones**: Soporta funciones en español (sen, tg, ln) y las convierte automáticamente

## 📝 Notas

- Las funciones matemáticas pueden escribirse usando notación estándar de JavaScript/Math.js
- Se soporta notación en español: `sen`, `tg`, `ln`, `ctg`, `csc` (se convierten automáticamente)
- Las constantes `pi` y `e` son reconocidas automáticamente
- Para funciones exponenciales, usa `exp(x)` o `e^x`

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 👨‍💻 Autor

Desarrollado como proyecto académico para Métodos Numéricos.

## 🙏 Agradecimientos

- [Math.js](https://mathjs.org/) - Librería de matemáticas para JavaScript
- [Chart.js](https://www.chartjs.org/) - Librería de gráficas

---

⭐ Si este proyecto te fue útil, considera darle una estrella en GitHub!

