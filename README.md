# App de consulta de ponderaciones (Streamlit)

## Qué hace
- Filtra por **Área** (determinada por el **color** de la columna A del Excel).
- Permite buscar por texto y seleccionar **varios grados**.
- Permite elegir **asignaturas** (todas o solo las que ponderan **0,2**).
- Devuelve un listado por **Grado + Universidad** con las **4 asignaturas** que ponderan (según selección).

> Nota: Los nombres de áreas se han inferido por el contenido de cada bloque de color:
> - Verde: Artes y Humanidades
> - Amarillo: Ciencias
> - Naranja: Ciencias (Medio ambiente/Geo)
> - Morado: Ciencias de la Salud
> - Azul: Ingeniería y Arquitectura
> - Rojo: Ciencias Sociales y Jurídicas

Si quieres que los nombres de áreas sean otros, dime el nombre exacto para cada color y lo ajusto.

## Cómo ejecutarla
1) Instala dependencias:
```bash
pip install streamlit openpyxl pandas
```

2) Coloca en la misma carpeta:
- `app.py`
- `PONDERACIONES ASIGNATURAS MOLINA.xlsx`

3) Ejecuta:
```bash
streamlit run app.py
```
