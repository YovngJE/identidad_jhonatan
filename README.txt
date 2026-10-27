REDISEÑO DE PORTAFOLIO — JHONATAN PEREA

Contenido:
- app.py: versión rediseñada para Python + Streamlit.
- imagenes/logo-jhonatan.png: logo cobre/café sin texto.

Cómo integrarlo:
1. Haz una copia de seguridad de tu app.py actual.
2. Reemplaza app.py por este archivo.
3. Copia la carpeta imagenes/ a la misma carpeta donde está app.py.
4. Conserva tu archivo proyectos.py junto a app.py; este rediseño sigue importando
   NOMBRE, UNIVERSIDAD, TEMAS y PROYECTOS desde ese archivo.
5. Conserva tu requirements.txt. Las dependencias indicadas son suficientes para
   este código: streamlit>=1.40, numpy, matplotlib y pillow.
6. Ejecuta: streamlit run app.py

No se incluye proyectos.py porque no fue adjuntado. El diseño utiliza la estructura
actual de proyectos: tema, titulo, desc, tags, imagen, repo y demo (estos dos últimos
son opcionales).
