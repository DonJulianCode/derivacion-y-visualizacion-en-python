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

```math
f(x) = (x - 3)^2
📁 Estructura del proyecto
Archivo/Sección	Descripción
notebook.ipynb	Notebook con implementación completa en Google Colab o Jupyter.
README.md	Este archivo. Explica propósito, estructura y decisiones.
funcion.py (opcional)	Código modularizado para usar fuera del notebook.

🧮 Pasos principales del análisis
Definición simbólica de la función y su derivada con SymPy.

Visualización de expresiones usando LaTeX y IPython.display.

Resolución simbólica del mínimo mediante derivación.

Conversión a función numérica usando lambdify.

Optimización numérica con scipy.optimize.minimize.

Gráfico combinado de la función y su derivada.

Comparación de resultados entre métodos.

📊 Resultados esperados
🧠 Simbólico:
ini
Copiar
Editar
x = 3.0,    f(x) = 0.0
⚙️ Numérico (SciPy):
scss
Copiar
Editar
x ≈ 2.9999999840660854,    f(x) ≈ 0.000000
Ambos métodos convergen al mismo mínimo, validando la precisión y consistencia del análisis.

🔍 Verificación
La diferencia absoluta entre ambos métodos es menor a $10^{-7}$:

python
Copiar
Editar
np.isclose(3.0, 2.9999999840660854, atol=1e-6)  # True
Esto confirma la fiabilidad del método numérico incluso sin conocer la derivada exacta.

🤖 Relevancia en Machine Learning
La optimización está en el corazón del entrenamiento de modelos de machine learning.
Este proyecto muestra cómo herramientas matemáticas (símbolo y número) se integran para:

Minimizar funciones de costo.

Validar resultados obtenidos por algoritmos de gradiente.

Enseñar fundamentos de optimización antes de aplicar modelos complejos.

🚀 Requisitos
Python 3.x

Bibliotecas: sympy, numpy, matplotlib, scipy, IPython

Instalación rápida:

bash
Copiar
Editar
pip install sympy numpy matplotlib scipy ipython
📌 Autor
Desarrollado por Julián Gómez Brizuela.
Parte del Proyecto Fénix de exploración simbólica, matemática y computacional con fines educativos.

🌱 Licencia
Este proyecto está disponible bajo la licencia MIT.
