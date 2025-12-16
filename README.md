# 🐍 Python – Apuntes, Resúmenes e Ideas

Este repositorio reúne **apuntes, resúmenes, fragmentos de código y experimentos en Python**.  
La idea es mantener un espacio organizado donde documentar aprendizajes, probar ideas y guardar ejemplos útiles para futuros proyectos.


## 🚀 Uso local

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/nabrick/Python.git
   cd Python
   ```

2. (Opcional) Crear un entorno virtual:

   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Linux/Mac
   .venv\Scripts\activate      # Windows
   ```

3. Instalar dependencias si aplica:

   ```bash
   pip install -r requirements.txt
   ```

## 📂 Estructura del repositorio

```
📂 python-apuntes/
 ┣ 📂 docs/           # Apuntes y resúmenes en Markdown
 ┣ 📂 ejemplos/       # Códigos de ejemplo y pruebas
 ┣ 📂 ideas/          # Bocetos de proyectos y experimentos
 ┣ mkdocs.yml         # Configuración de MkDocs (para visualización local)
 ┗ LICENSE            # Licencia AGPL-3.0
```


## 📖 Visualización local (opcional)

Para ver los apuntes y resúmenes con una interfaz más amigable puedes usar **MkDocs** y el tema **Material**:

```bash
pip install mkdocs-material
mkdocs serve
```

Abrir en [http://127.0.0.1:8000](http://127.0.0.1:8000)


## ⚖️ Licencia
Este repositorio está publicado bajo la licencia **AGPL-3.0**.
Consulta el archivo [LICENSE](./LICENSE) para ver el texto completo.

El despliegue local de la documentación utiliza **MkDocs** y el tema **Material for MkDocs**, ambos bajo licencia **MIT**. Estas herramientas no modifican la licencia del contenido de este repositorio.