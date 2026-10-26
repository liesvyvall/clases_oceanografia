# Guía de instalación: Anaconda y Jupyter Notebook

Clase 01: Campaña oceanográfica virtual en la Bahía de La Paz (diagrama T–S)

Esta guía explica cómo preparar tu computadora para correr el notebook
`diagrama_TS_bahia_la_paz.ipynb`.

---

## Paso 1. Descargar Anaconda

1. Entra a <https://www.anaconda.com/download>.
2. Si te pide registrarte, da clic en **Skip registration**.
3. Descarga el instalador para tu computadora:
   - **Windows:** el archivo `.exe`.
   - **Mac:** el archivo `.pkg`. Si tu Mac tiene procesador M1, M2, M3, etc., elige
     **Apple Silicon**; si es Intel, elige **Intel**.

## Paso 2. Instalar Anaconda

Abre el archivo que descargaste y da clic en **Siguiente** (*Next*) en todas las pantallas,
dejando las opciones que vienen por defecto. Al final da clic en **Finalizar** (*Finish*).

## Paso 3. Instalar las librerías de la clase

1. Abre la terminal:
   - **Windows:** en el menú Inicio busca y abre **Anaconda Prompt**.
   - **Mac:** abre la aplicación **Terminal**.
2. Escribe lo siguiente y presiona Enter:

   ```
   pip install copernicusmarine gsw cmocean
   ```

3. Espera a que termine. Al final debe decir `Successfully installed`.

## Paso 4. Descargar el material de la clase

1. Entra a <https://github.com/liesvyvall/clases_oceanografia>.
2. Da clic en el botón verde **Code** y luego en **Download ZIP**.
3. Descomprime el archivo y guarda la carpeta en **Documentos**.

El notebook y la carpeta `datos/` deben quedar juntos, sin moverlos:

```
clases_oceanografia/
└── 01_diagrama_TS_bahia_la_paz/
    ├── diagrama_TS_bahia_la_paz.ipynb
    └── datos/
```

## Paso 5. Abrir el notebook

1. Abre **Anaconda Navigator**.
2. En el cuadro de **Jupyter Notebook** da clic en **Launch**.
3. Se abre tu navegador. Entra a `Documents` → `clases_oceanografia` →
   `01_diagrama_TS_bahia_la_paz` y da clic en `diagrama_TS_bahia_la_paz.ipynb`.

## Paso 6. Correr el notebook

- Haz clic en una celda y presiona **Shift + Enter** para correrla.
- Corre las celdas en orden, de arriba hacia abajo.

Los datos ya vienen en la carpeta `datos/`, así que no necesitas cuenta de Copernicus Marine.
Deja la celda de `copernicusmarine.login()` con el `#` como viene.
