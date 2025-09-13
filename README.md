# 📊 Proyección de Ventas con Variables Macroeconómicas

Esta aplicación en **Streamlit** permite cargar datos históricos de
ventas y variables macroeconómicas (PIB, Desempleo, Tipo de Cambio,
Inflación) para realizar proyecciones de ventas mediante **regresiones
lineales simples** y un modelo de **pronóstico ponderado por R²**.

------------------------------------------------------------------------

## 🚀 Funcionalidades

-   Carga de archivos **CSV o Excel** con datos históricos.
-   Limpieza y normalización automática de columnas (quita acentos,
    espacios, símbolos `%`, `$`, `,`).
-   Conversión de proporciones a **puntos porcentuales (0--100)**.
-   Estimación de regresiones lineales simples:
    -   Correlación.
    -   Pendiente (β).
    -   Intersección (α).
    -   R².
-   Pronóstico de ventas basado en escenarios definidos por el usuario.
-   Exportación de resultados a **Excel** con tres hojas:
    1.  Datos Históricos
    2.  Regresiones
    3.  Pronósticos

------------------------------------------------------------------------

## 📂 Requisitos

Instalar dependencias desde `requirements.txt`:

``` bash
pip install -r requirements.txt
```

Dependencias principales: - streamlit - pandas - numpy - scikit-learn -
xlsxwriter - openpyxl

------------------------------------------------------------------------

## ▶️ Cómo ejecutar la app

1.  Clona el repositorio o descarga los archivos `app.py` y
    `requirements.txt`.
2.  Instala las dependencias.
3.  Ejecuta el siguiente comando:

``` bash
streamlit run app.py
```

4.  Abre el enlace generado en tu navegador (por defecto:
    `http://localhost:8501`).

------------------------------------------------------------------------

## 📥 Uso de la aplicación

1.  **Subir archivo histórico** (CSV o Excel) con las siguientes
    variables:

    -   `PIB`
    -   `Desempleo`
    -   `TipoCambioPct`
    -   `Inflacion`
    -   `Ventas`

2.  **Visualizar y validar los datos** tras la limpieza automática.

3.  **Consultar las regresiones simples** y métricas (Correlación, β, α,
    R²).

4.  **Definir escenarios futuros** desde la barra lateral (PIB,
    Desempleo, Tipo de Cambio, Inflación).

5.  **Obtener el pronóstico de ventas** individual y el pronóstico
    ponderado.

6.  **Descargar los resultados en Excel** con un clic.

------------------------------------------------------------------------

## 📸 Capturas de Pantalla (opcional)

> Aquí puedes añadir imágenes de la app en ejecución.

------------------------------------------------------------------------

## 🛠️ Autor

Aplicación desarrollada en **Python + Streamlit** para análisis y
pronóstico de ventas basado en variables macroeconómicas.
