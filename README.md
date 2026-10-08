# Simulación Interactiva de un Cúbit en la Esfera de Bloch

Notebook que permite explorar el espacio de estados de un cúbit y visualizar
cómo actúan las puertas cuánticas de un qúbit sobre la esfera de Bloch, mediante
un menú interactivo.

## Probar la simulación

Para usar los menús interactivos hace falta ejecutar el notebook (GitHub solo lo
muestra de forma estática). Puedes hacerlo sin instalar nada con cualquiera de
estas dos opciones:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RodrigoHernandezSacristan/Esfera-de-Bloch/blob/main/Bloch_SphereDefinitivo.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/RodrigoHernandezSacristan/Esfera-de-Bloch/main?labpath=Bloch_SphereDefinitivo.ipynb)

- **Google Colab**: abre el notebook en la nube y ejecútalo con *Entorno de
  ejecución → Ejecutar todo*. Los menús interactivos funcionan directamente.
- **Binder**: lanza un entorno Jupyter completo a partir de este repositorio.
  Tarda un poco en arrancar la primera vez.

## Ejecutar en local

```bash
git clone https://github.com/RodrigoHernandezSacristan/Esfera-de-Bloch.git
cd Esfera-de-Bloch
pip install -r requirements.txt
jupyter notebook Bloch_SphereDefinitivo.ipynb
```

## Dependencias

Ver `requirements.txt`. En resumen: `qiskit`, `matplotlib`, `numpy` e
`ipywidgets`.
