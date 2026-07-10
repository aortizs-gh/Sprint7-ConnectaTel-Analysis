# Sprint7-ConnectaTel-Analysis
- OBJETIVO DEL PROYECTO:
Como Analista de Datos en ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia, se deberá entregar un reporte para que ConnectaTel entienda cómo se comportan sus usuarios según edad, volumen de llamadas/mensajes y nivel de consumo.
El objetivo de la empresa es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.
El entregable será un análisis completo (distribuciones, outliers, segmentación y oportunidades comerciales) acompañado de un notebook limpio y reproducible.
   
- DATASETS UTILIZADOS
  Son tres fuentes principales de información, relacionadas con usuarios, actividad y planes del servicio de ConnectTel:
1.	plans.csv: Catálogo de planes con sus precios y beneficios.
2.	users_latam.csv: Información de cada usuario (datos personales, plan, fecha de registro, churn). 
3.	usage.csv: Actividad generada por los usuarios: llamadas, mensajes, duración, longitud.

- ETAPAS DEL ANÁLISIS
1. Cargar y explorar datasets =	Visión clara de la estructura y tipos de columna de cada dataset.
2. Identificación de problemas de calidad	= Detectar problemas de sesgo con conteo de nulos, detección de sentinels, revisión de fechas fuera de rango.	
3. Limpieza básica = Reemplazar sentinels, convertir fechas, imputar o marcar NA según reglas para generar datos consistentes y listos para análisis estadístico.
4. Summary statistics	= Revisar las medidas clave en variables categóricas y numéricas que muestren el comportamiento típico y extremo
5. Visualización & outliers	= Creación de histogramas y boxplots para visualización de sesgos, patrones de usuarios o datos atípicos.
6. Segmentación = Crear segmentaciones basadas en reglas claras y visualizar proporciones con countplots que permitan diseñar ofertas, campañas y migraciones de plan.
7. Insight ejecutivo =	Redactar conclusiones y recomendaciones comerciales basadas en los pasos anteriores.	
8. Publicación =	Subir Notebook + README a GitHub, de manera que pueda ser reproducible para revisión y ejecución por stakeholders.
    
- CÓMO EJECUTAR EL NOTEBOOK (POR EJEMPLO, ABRIRLO EN GOOGLE COLAB)
  Para abrir el presente Notebook en Google Colab puedes accionar el botón "Open in colab" que aparece en la parte superior izquierda de inicio del Notebook 
  En la interfaz de Colab, ve a la pestaña GitHub, pega el enlace del repositorio o nombre de usuario.
  También puedes hacerlo rápidamente añadiendo https://colab.research.google.com/github/ antes de la URL del repositorio. 
   
- BREVE GUÍA DE REPRODUCCIÓN
  En el repositorio en GitHub, haz clic en el botón verde Code.
  Selecciona la pestaña Codespaces y haz clic en Create codespace on main. Esto abrirá un entorno completo de Jupyter Lab en tu propio navegador.
