<h1 align="center">F1 Tire Degradation Prediction</h1>
<p align="center">
  <b>Python · Machine Learning · scikit-learn · Matplotlib · NumPy</b><br>
  Simple linear regression predicting tyre wear per lap over a 71-lap race
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&labelColor=0D0D0D">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&labelColor=0D0D0D">
  <img src="https://img.shields.io/badge/Matplotlib-3F4F75?style=for-the-badge&labelColor=0D0D0D">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&labelColor=0D0D0D">
</p>

---

## EN

A hands-on introduction to **simple linear regression**, using Formula 1 tyre
degradation as the problem.

### The problem

Simulate a **71-lap race** and predict how much tyre performance is lost on each
lap. The simulation accounts for the things that actually change grip during a
race:

- **Medium** and **hard** compound behaviour
- A **pit stop** — fresh rubber on new tyres
- **Cooling effects** of the circuit

Synthetic data is generated, a linear regression model is trained on it, and the
result is plotted against the simulated ground truth.

### Why this example

Linear regression is the most fundamental algorithm in machine learning, and
tyre wear is a genuinely linear-looking problem: a tyre loses a roughly constant
amount of grip per lap, and the constants change when you pit. That makes it a
good vehicle for understanding fit, residuals and prediction without the noise
of a harder problem.

### How to run

Built for **Google Colab** — no local setup needed.

1. Open the notebook in Colab
2. **Runtime → Run all**

Or locally:

```bash
pip install numpy scikit-learn matplotlib jupyter
jupyter notebook PROYECTOS.ipynb
```

---

## ES

Introducción práctica a la **regresión lineal simple**, usando el desgaste de
neumáticos de Fórmula 1 como problema.

### El problema

Simular una **carrera de 71 vueltas** y predecir cuánta performance se pierde enperformance se pierde en
cada vuelta. La simulación tiene en cuenta lo que realmente cambia el grip
durante una carrera:

- Comportamiento de compuestos **medios** y **duros**
- Una **parada en boxes** — goma nueva sobre neumáticos nuevos
- **Efectos de enfriamiento** de la pista

Se generan datos sintéticos, se entrena un modelo de regresión lineal y se grafica
el resultado contra la verdad simulada.

### Por qué este ejemplo

La regresión lineal es el algoritmo más fundamental del machine learning, y el
desgaste de neumáticos es un problema que *parece* genuinamente lineal: un
neumático pierde una cantidad aproximadamente constante de grip por vuelta, y
esa constante cambia al entrar a boxes. Eso lo convierte en un buen caso para
entender ajuste, residuales y predicción sin el ruido de un problema más difícil.

### Cómo ejecutarlo

Pensado para **Google Colab** — no hace falta instalar nada localmente.

1. Abrí el notebook en Colab
2. **Runtime → Run all**

O localmente:

```bash
pip install numpy scikit-learn matplotlib jupyter
jupyter notebook PROYECTOS.ipynb
```

---

## Licencia

MIT — ver [LICENSE](LICENSE).
