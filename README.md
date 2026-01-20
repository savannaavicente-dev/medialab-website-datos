# medialab-website-datos
Proyecto: Website académico/Tech con dataset de titulares del Blog de PythonObjetivo: Demonstrar flujo reproducible de extracción y procesamiento de datos para comunicación digital.Fuente: https://blog.python.org/ (consulta automatizada)Outputs:
data/posts_python_blog.csv (titulares + URLs)
data/posts_python_blog_procesado.csv (+ longitud de título)
data/top_palabras_titulos.csv (top 20 palabras)
Cómo correr:
pip install requests beautifulsoup4 pandas
python src/scrape_python_blog.py
python src/process_posts.py

Website: publicado con GitHub Pages en /docs.

<img width="855" height="326" alt="image" src="https://github.com/user-attachments/assets/1d5701a1-6487-47b7-9b39-a900e4e425d0" />
