# 🎬 Análisis de Datos con SQL - Base de Datos Sakila

Este proyecto analiza la base de datos Sakila para extraer insights sobre el negocio del alquiler de películas.  

## 📌 Objetivos
🔹 Identificar las películas más rentadas.  
🔹 Analizar el comportamiento de los clientes.  
🔹 Determinar los géneros más rentables.  
🔹 Evaluar los ingresos mensuales de la tienda.  

## 🔍 Consultas Utilizadas
✅ Listar todas las tablas de la base de datos.  
✅ Películas más rentadas.  
✅ Clientes más activos.  
✅ Géneros con mayores ingresos.  
✅ Análisis de ingresos mensuales.  

## 📊 Visualizaciones  
Aquí algunos gráficos clave del análisis:

![Películas más rentadas](visualizaciones/top_peliculas.png)  
![Géneros más rentables](visualizaciones/ingresos_genero.png)  

## 🚀 Cómo Usar Este Proyecto  
1️⃣ Clonar este repositorio:  
```bash
git clone https://github.com/tu-usuario/proyecto-sql-sakila.git
```
2️⃣ Descarga la base de datos desde Kaggle utilizando `kagglehub` en Google Colab:  
```python
import kagglehub
path = kagglehub.dataset_download("atanaskanev/sqlite-sakila-sample-database")
```
3️⃣ Conéctate a la base de datos:  
```python
import sqlite3
import os
db_path = os.path.join(path, "sqlite-sakila.db")
conn = sqlite3.connect(db_path)
```
4️⃣ Ejecuta las consultas SQL en Google Colab.  

## 📝 Contribución  
Si deseas contribuir a este proyecto:  
1. Realiza un fork del repositorio.  
2. Crea una rama con tu nueva característica (`git checkout -b feature-nueva`).  
3. Realiza los cambios y sube la rama (`git push origin feature-nueva`).  
4. Abre un Pull Request.  

## 📚 Licencia  
Este proyecto está bajo la licencia MIT. Puedes ver más detalles en el archivo [LICENSE](LICENSE).  

---  
**Autor:** José Miguel Henríquez Arrau

## 📢 Contacto
📩 **jose.miguelhen@gmail.com**  
🔗 [LinkedIn](https://www.linkedin.com/in/jos%C3%A9-miguel-henr%C3%ADquez-arrau-sociologo-fullstack-web/)  


