# 🚀 Reto RAG – Certificado en Desarrollo de Software con IA Generativa

Este proyecto implementa un sistema **RAG (Retrieval-Augmented Generation)** como parte del reto del certificado en desarrollo de software con IA Generativa.

---

## 📌 Objetivos del reto
- Aplicar principios básicos de IA generativa.
- Implementar un pipeline completo de RAG.
- Configurar un sistema de CI/CD automatizado con GitHub Actions.
- Identificar oportunidades para usar IA en proyectos reales.

---

## ⚙️ Tecnologías usadas
- Python 3.10
- LangChain
- ChromaDB
- OpenAI API
- GitHub Actions (CI/CD)

---

## 📂 Estructura del proyecto
reto_ragCursoIA/
├── data/ # Documentos PDF usados como fuente
├── notebooks/ # Notebook principal del reto
│ └── RETO_RAG.ipynb
├── requirements.txt # Librerías necesarias
└── .github/workflows/ # CI/CD con GitHub Actions


---

## ▶️ Ejecución local

1. **Clonar este repositorio**
   ```bash
   git clone https://github.com/jrolas10/reto_rag_curso_ia

python -m venv .venv
.venv\Scripts\activate   # Windows
source .venv/bin/activate  # Linux/Mac


pip install -r requirements.txt


OPENAI_API_KEY=xxxx
## 🔄 CI/CD en GitHub
Cada `git push` ejecuta automáticamente el notebook en **GitHub Actions** y guarda el resultado como `artifact` (`output.ipynb`).

---

## 🧪 Pruebas realizadas
Se realizaron 5 consultas al sistema RAG, entre ellas:

- ¿Cómo se prepara la receta de hot cakes?  
- ¿Qué ingredientes principales llevan los hot cakes?  
- ¿Qué pasos básicos se recomiendan para instalar el router?  

---

## 📖 Reflexiones
- Logré implementar un RAG completo y automatizado.  
- GitHub Actions facilitó validar la ejecución sin depender de mi PC.  
- El tamaño de los *chunks* y los documentos influyen en la calidad de las respuestas.  
- Como mejora futura, incluiría más documentos y pruebas más amplias.  
