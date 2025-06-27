# 🧠 Optimización Simbólica y Numérica en Python

Este proyecto demuestra cómo aplicar y comparar dos enfoques para encontrar el mínimo de una función cuadrática:

- ✅ **Optimización simbólica** con [SymPy](https://www.sympy.org/): usando derivación exacta.
- ⚙️ **Optimización numérica** con [SciPy](https://scipy.org/): utilizando el método `minimize`.

---

## 🎯 Objetivo

Ilustrar, de forma didáctica y visual, cómo se puede resolver un problema clásico de optimización mediante:

- Derivadas simbólicas.
- Métodos numéricos.
- Visualización gráfica con `Matplotlib`.

Todo esto aplicado sobre una función cuadrática convexa simple:

$$
f(x) = (x - 3)^2
$$

---

## 📁 Estructura del proyecto

| Archivo/Sección | Descripción |
|-----------------|-------------|
| `notebook.ipynb` | Notebook con implementación completa en Google Colab o Jupyter. |
| `README.md` | Este archivo. Explica propósito, estructura y decisiones. |
| `funcion.py` (opcional) | Código modularizado para usar fuera del notebook. |

---

## 🧮 Pasos principales del análisis

1. **Definición simbólica** de la función y su derivada con `SymPy`.
2. **Visualización** de expresiones usando LaTeX y `IPython.display`.
3. **Resolución simbólica** del mínimo mediante derivación.
4. **Conversión a función numérica** usando `lambdify`.
5. **Optimización numérica** con `scipy.optimize.minimize`.
6. **Gráfico combinado** de la función y su derivada.
7. **Comparación de resultados** entre métodos.

---

📌 Autor
Desarrollado por Julián Gómez Brizuela.

🌱 Licencia
Este proyecto está disponible bajo la licencia MIT.
