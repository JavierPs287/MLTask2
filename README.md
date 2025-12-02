ISO BROS

## Como crear el entorno

### 1. Crear el entorno virtual
```bash
python3 -m venv .venv
```
- Esto hay que hacerlo fuera de el directorio de el repo*

### 2. Activar el entorno virtual

```bash
source venv/bin/activate 
```
o 
```bash
venv\Scripts\activate
```

### 3.Instalar dependencias
```bash
pip install -r requirements.txt
```

### 5.Descargar NLTK
```bash
python -c "import nltk; nltk.download('stopwords'); nltk.download('punkt'); nltk.download('wordnet'); nltk.download('punkt_tab')"
```
## 