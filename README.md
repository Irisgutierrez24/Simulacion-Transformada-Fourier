# Simulación y análisis de señales con la Transformada de Fourier

## Descripción del proyecto

Este proyecto tiene como finalidad analizar señales digitales en el dominio del tiempo y de la frecuencia mediante la Transformada de Fourier, utilizando Python y bibliotecas especializadas para el procesamiento y visualización de señales.

Se desarrollaron tres señales elementales: pulso rectangular, función escalón y señal senoidal. Posteriormente, se calculó su Transformada Discreta de Fourier (DFT) mediante el algoritmo FFT para estudiar sus espectros de magnitud y fase.

## Objetivos

- Representar señales en el dominio del tiempo.
- Aplicar la Transformada de Fourier utilizando Python.
- Visualizar los espectros de magnitud y fase.
- Analizar las propiedades de linealidad, desplazamiento temporal y escalamiento en frecuencia.
- Comparar los resultados obtenidos en ambos dominios.

## Tecnologías utilizadas

- Python 3
- Jupyter Notebook
- NumPy
- SciPy
- Pandas
- Matplotlib

## Señales implementadas

| Señal | Características |
|---|---|
| Pulso rectangular | Amplitud 1 entre 0.2 y 0.4 segundos. |
| Función escalón | Cambio de amplitud de 0 a 1 en 0.5 segundos. |
| Señal senoidal | Frecuencia de 50 Hz y amplitud de 1. |

## Parámetros de simulación

| Parámetro | Valor |
|---|---:|
| Frecuencia de muestreo | 1000 Hz |
| Duración | 1 segundo |
| Número de muestras | 1000 |
| Frecuencia senoidal | 50 Hz |

## Propiedades de Fourier verificadas

**1. Linealidad:** se comprobó que la transformada de una combinación lineal de señales coincide con la combinación lineal de sus transformadas.

**2. Desplazamiento temporal:** se verificó que el desplazamiento en el tiempo conserva la magnitud del espectro y modifica la fase.

**3. Escalamiento en frecuencia:** se comprobó que al duplicar la frecuencia de una señal de 50 Hz se obtiene una señal de 100 Hz.

## Estructura del proyecto

```text
Simulacion-Transformada-Fourier/
│
├── README.md
├── Transformada_Fourier.ipynb
│
└── resultados/
    ├── pulso_rectangular.png
    ├── espectros de las señales
    ├── comparaciones
    └── gráficas de propiedades de Fourier
```

## Resultados

Las simulaciones permitieron observar que cada señal presenta características diferentes en el dominio de la frecuencia.

El pulso rectangular presenta múltiples componentes frecuenciales; la función escalón contiene una componente continua y otras componentes distribuidas; y la señal senoidal presenta un pico principal en 50 Hz.

También se comprobó el cumplimiento de las propiedades de linealidad, desplazamiento temporal y escalamiento en frecuencia.

## Ejecución del proyecto

1. Instalar Python.
2. Instalar las bibliotecas necesarias:

```bash
pip
