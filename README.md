# Protect PDF

Editor de archivos PDF en línea para:

- Subir múltiples archivos PDF
- Reordenarlos y eliminarlos
- Unirlos en uno solo
- Vista previa del archivo final
- Proteger contra edición (requiere backend)

## 🧰 Tecnologías

- Frontend: HTML, CSS, JavaScript, [PDF-Lib](https://pdf-lib.js.org/)
- Backend: Python, Flask, pypdf

## 🚀 Instrucciones de uso

### Clonar el repositorio

```bash
git clone https://github.com/edu78py/protect-pdf.git
cd protect-pdf
```

### Crear entorno virtual

```bash
python -m venv venv
.\venv\Scripts\activate
```

### Instalar dependencias

```bash
pip install -r requirements.txt
```

### Correr el backend

```bash
python app.py
```

### Abrir `index.html` en el navegador

Funciona de forma local sin necesidad de servidor para el frontend.
