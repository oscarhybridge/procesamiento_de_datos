# **Laboratorio 2: Preprocesamiento de Datos**

Este repositorio contiene los notebooks necesarios para el laboratorio de preprocesamiento de datos, donde se explorarán técnicas fundamentales como manejo de datos faltantes, escalado y codificación de variables. Cada notebook incluye ejercicios prácticos y preguntas que los estudiantes deberán resolver utilizando Python.

---

## **Contenido del repositorio**

- **`1_datos_faltantes.ipynb`**: Aprende a identificar y manejar datos faltantes utilizando técnicas como imputación simple y avanzada.
- **`2_escalado.ipynb`**: Explora técnicas de escalado como MinMaxScaler y StandardScaler para normalizar las variables.
- **`3_codificacion_de_variables.ipynb`**: Descubre cómo convertir variables categóricas a formatos numéricos mediante Label Encoding y One-Hot Encoding.

---

## **Requisitos previos**

Asegúrate de tener instalado lo siguiente en tu sistema:
- Python 3.7 o superior
- pip (gestor de paquetes de Python)

---

## **Tutorial para configurar el entorno**

### 1. Crear un entorno virtual
Un entorno virtual te permite mantener aisladas las dependencias del proyecto. Sigue estos pasos:

#### En sistemas Windows:
```bash
python -m venv venv
```

#### En sistemas MacOS/Linux:
```bash
python3 -m venv venv
```

### 2. Activar el entorno virtual

#### En sistemas Windows:
```bash
venv\Scripts\activate
```

#### En sistemas MacOS/Linux:
```bash
source venv/bin/activate
```

Cuando el entorno virtual esté activado, verás un prefijo `(venv)` en tu terminal.

---

### 3. Instalar las dependencias
Este repositorio ya incluye un archivo `requirements.txt` con todas las dependencias necesarias. Una vez que el entorno virtual esté activado, instala las dependencias ejecutando:

```bash
pip install -r requirements.txt
```

Esto instalará automáticamente las librerías necesarias, como `pandas`, `scikit-learn`, `seaborn`, y otras.

---

## **Cómo usar los notebooks**

1. Asegúrate de tener el entorno virtual activado.
2. Inicia Jupyter Lab desde la terminal:
   ```bash
   jupyter lab
   ```
3. Abre cualquiera de los notebooks (`datos_faltantes.ipynb`, `escalado.ipynb`, `codificacion_variables.ipynb`) y sigue las instrucciones para completar las actividades.