<div align="center">

<p align="left"><strong><samp>「</samp></strong></p>

<samp>
<b>
¡Hola! 👋 Soy:
<br>
<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://www.gitskins.com/api/section/wordmark?username=nodexs0&theme=aurora&avatar=https%3A%2F%2Favatars.githubusercontent.com%2Fu%2F138817295%3Fu%3Dfee18997ede0c278ea51a77b66370aa5233b417c%26v%3D4&label=Mariano&v=cinematic-hero-wordmark-1&mode=light" />
  <img src="https://www.gitskins.com/api/section/wordmark?username=nodexs0&theme=aurora&avatar=https%3A%2F%2Favatars.githubusercontent.com%2Fu%2F138817295%3Fu%3Dfee18997ede0c278ea51a77b66370aa5233b417c%26v%3D4&label=Mariano&v=cinematic-hero-wordmark-1&mode=dark" width="100%" alt="Mariano animated ASCII name" />
</picture>
<b>
También conocido como nodexs0 :D
<br>
Egresado de Ingeniería en Inteligencia Artificial en el <span style="color: #6F1C38;">IPN</span>.
</b>
<br>
<img src="https://readme-typing-svg.demolab.com/?font=Iosevka&size=16&color=4A6FA5&center=true&width=600&height=45&lines=Me+gustan+los+desaf%C3%ADos+y+resolver+problemas+a+trav%C3%A9s+de+c%C3%B3digo.;Machine+Learning+%E2%80%A2+Deep+Learning+%E2%80%A2+Computer+Vision.;3er+lugar+en+Hackathon+Tech+Capital+2025.;Full+Stack+Development.;Siempre+aprendiendo+algo+nuevo.">
</samp>

<p align="right"><strong><samp>」</samp></strong></p>

</div>

<br>

## 🧠 Sobre mí

Soy egresado de Ingeniería en Inteligencia Artificial por el Instituto Politécnico Nacional (IPN). Me apasiona resolver problemas complejos a través de código, con experiencia enfocada en visión por computadora, procesamiento de señales y desarrollo de aplicaciones móviles que integran modelos de IA en tiempo real.

- 🔭 Interesado en aplicar y seguir desarrollando mis habilidades en programacion e IA para resolver problemas reales.
- 🌱 Aprendiendo constantemente nuevas herramientas del ecosistema de ML/DL, visión por computadora.
- 💬 Pregúntame sobre Python, redes neuronales, visión por computadora o desarrollo de apps móviles con IA integrada.
- ⚡ Me gustan los desafíos técnicos y la programación competitiva.

<br>

## 🛠️ Stack principal

<p align="center">
<a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/></a>
<a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="fastapi" width="40" height="40"/></a>
<a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/></a>
<a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="mongodb" width="40" height="40"/></a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" width="40" height="40"/></a>
</p>

<br>

## 📌 Proyectos destacados

### 🏆 [Clasificación de Llanto de Bebés — Hackathon Tech Capital 2025](https://www.facebook.com/inaoe.oficial/posts/buenasnoticias-en-el-marco-de-tech-capital-puebla-summit-2025-se-convoca-a-estud/1108117431434487/)
**3er lugar** en el Hackathon Tech Capital 2025 (Puebla), como parte del equipo **NeuroStar Debbugers**. El reto consistía en desarrollar una solución de IA capaz de clasificar automáticamente vocalizaciones de llanto de bebés para identificar posibles condiciones de salud (asfixia, hipoacusia, hiperbilirrubinemia, hipotiroidismo o llanto sano) a partir de grabaciones de audio, utilizando computación paralingüística.

- Análisis exploratorio y preprocesamiento del dataset de audios etiquetados.
- Generación de espectrogramas de Mel a partir de las señales de audio (`n_fft=2048`, `n_mels=35`, ventana Hann con 25% de traslape).
- Entrenamiento de un modelo CNN (transfer learning con **VGG-16** preentrenado en ImageNet) sobre los espectrogramas para clasificar entre 5 clases.
- Resultado: **89% de exactitud** en el conjunto de prueba.

`Python` `TensorFlow` `Librosa` `CNN` `VGG-16` `Procesamiento de señales`

---

### 🤖 [AlphaByte — Robot con visión que sigue personas](https://github.com/nodexs0/AlphaByte)
Robot construido para una feria de ciencias de mi unidad académica, capaz de detectar y seguir personas en tiempo real combinando hardware embebido con visión por computadora.

- Detección de personas en tiempo real con **YOLO**.
- Streaming de video y control del robot mediante **ESP32-CAM**.
- Lógica de seguimiento en **Python** para ajustar el movimiento del robot según la posición de la persona detectada.

`Python` `YOLO` `ESP32-CAM` `OpenCV` `Visión por computadora`

---

### ♻️ [ReciclApp — Clasificador de basura reciclable/no reciclable](https://github.com/etmoji/PF_ReciclApp_ReactN)
Aplicación móvil que clasifica residuos en 7 categorías (cartón, compost, vidrio, metal, papel, plástico y basura no reciclable) y muestra centros de acopio cercanos para cada tipo de material.

- Dataset propio construido a partir de la combinación de 4 datasets públicos (TrashNet, OpenRecycle, TACO y Wasted Classification), totalizando **8,134 imágenes**.
- Modelo basado en **MobileNetV2** + capas de **Multi-Head Attention** para mejorar la precisión de clasificación frente a un CNN convencional.
- **93.77% de exactitud** en el conjunto de prueba, con métricas más altas en clases como compost y cartón.
- Aplicación móvil desarrollada en **React Native** para geolocalizar centros de acopio cercanos.

`Python` `TensorFlow` `React Native` `MobileNetV2` `Multi-Head Attention`

---

### 👥 [Conteo de Personas — App móvil con visión en tiempo real](https://github.com/nodexs0/conteo-personas-app)
Aplicación móvil desarrollada para contar personas dentro de una sala en tiempo real, registrando entradas y salidas para llevar un control de aforo (probada en un salón de clases).

- Detección de personas con **YOLO** y seguimiento de identidades con **DeepSORT** para evitar doble conteo.
- Backend con **FastAPI** que recibe frames de la app y devuelve el conteo actualizado.
- App móvil multiplataforma en **React Native**, con historial de reportes, modo oscuro e inicio de sesión.
- Metodología de trabajo en equipo con **Scrum** y seguimiento en Trello.

`Python` `YOLO` `DeepSORT` `FastAPI` `React Native`


<br>

## 💼 Experiencia

### 🏢 Super Rivera S.A. de C.V.
#### **Desarrollador Junior** | *2026 – Presente*
Actualmente participo en el desarrollo de PLACOR, una plataforma empresarial para la gestión de inventarios, pedidos y análisis de ventas utilizada por una cadena de supermercados, desarrollando módulos tanto de frontend como de backend y gestionando la infraestructura de la aplicación.

<div>

![Backend](https://img.shields.io/badge/Backend-4A6FA5?style=for-the-badge&logo=fastapi&logoColor=white)
![Frontend](https://img.shields.io/badge/Frontend-4A6FA5?style=for-the-badge&logo=react&logoColor=white)
![Database](https://img.shields.io/badge/Database-4A6FA5?style=for-the-badge&logo=mongodb&logoColor=white)
![DevOps](https://img.shields.io/badge/DevOps-4A6FA5?style=for-the-badge&logo=docker&logoColor=white)

</div>

`Python` `FastAPI` `MongoDB` `React` `TypeScript` `Tailwind CSS` `Docker` `Nginx` `Playwright`


<br>

## 🎓 Formación

### 🏛️ Ingeniería en Inteligencia Artificial
**Instituto Politécnico Nacional (UPIIT-IPN)**
*2022 – 2026*

- Formación en Inteligencia Artificial, Machine Learning y Visión por Computadora.
- Desarrollo de aplicaciones web y móviles full stack.
- Procesamiento digital de señales, bases de datos y arquitectura de software.
- Desarrollo e implementación de modelos de IA aplicados a problemas reales.

#### 🏅 Actividades destacadas

- 🏆 3.er lugar en el Hackathon Tech Capital 2025.
- 👨‍🏫 Tutor de programación en UPIIT-IPN, apoyando a estudiantes en algoritmos, estructuras de datos, C++ y Python.
- 🤖 Desarrollo de un robot autónomo con visión por computadora presentado en la Feria de Ciencias UPIIT 2024.
---

### 💻 Técnico en Programación
**CBTis No. 212**
*2018 – 2021*

- Formación en programación orientada a objetos.
- Desarrollo con C#, C++, Java y PHP.
- Diseño y administración de bases de datos.
- Desarrollo de aplicaciones web y de escritorio.

---

### 🖥️ Secundaria Técnica No. 9
**Especialidad en Informática**
*2015 – 2018*

- Primer acercamiento al desarrollo de software.
- Aprendizaje de lógica de programación y algoritmos básicos.
- Introducción a C++, marcando el inicio de mi interés por la programación y la tecnología.

---

### 📖 Formación continua

Además de mi formación académica, mantengo un aprendizaje autodidacta mediante proyectos personales y el estudio constante de nuevas tecnologías relacionadas con:

- 🤖 Inteligencia Artificial y Computer Vision.
- 🌐 Desarrollo Full Stack.
- 🐳 Docker, Linux y DevOps.
- ☁️ Arquitecturas backend y despliegue de aplicaciones.
- 📊 Algoritmia y estructuras de datos.

<br>

## 🌐 Idiomas

- **Español:** Nativo
- **Inglés:** Technical reading and documentation.

<br>

## 🧩 Tecnologías con las que he trabajado

<table>
<tr>
<td valign="top" width="25%">

### 🤖 IA

<p align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40"/>
<img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" width="40"/>
<img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" width="40"/>
<img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" width="40"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width="40"/>
<img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" width="40"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" width="40"/>

</p>

TensorFlow<br>
PyTorch<br>
OpenCV<br>
Scikit-Learn<br>
Pandas<br>
Seaborn<br>
MATLAB

</td>

<td valign="top" width="25%">

### 🌐 Frontend

<p align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="40"/>
<img src="https://reactnative.dev/img/header_logo.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" width="40"/>
<img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" width="40"/>
<img src="https://www.chartjs.org/media/logo-title.svg" width="40"/>

</p>

React<br>
React Native<br>
TypeScript<br>
JavaScript<br>
Tailwind CSS<br>
Bootstrap<br>
Chart.js

</td>

<td valign="top" width="25%">

### ⚙️ Backend

<p align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-plain.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="40"/>
<img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" width="40"/>

</p>

FastAPI<br>
Django<br>
Flask<br>
Node.js<br>
Firebase

</td>

<td valign="top" width="25%">

### 🗄️ Bases de datos

<p align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original.svg" width="40"/>

</p>

MongoDB<br>
PostgreSQL<br>
MySQL<br>
SQLite

</td>
</tr>
<tr>

<td valign="top" width="25%">

### 🐳 DevOps

<p align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" width="40"/>
<img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" width="40"/>
<img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" width="40"/>

</p>

Docker<br>
Nginx<br>
Linux<br>
Git<br>
Bash<br>
Heroku<br>
Postman

</td>

<td valign="top" width="25%">

### 📱 Mobile

<p align="center">

<img src="https://reactnative.dev/img/header_logo.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original.svg" width="40"/>
<img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" width="40"/>
<img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" width="40"/>

</p>

React Native<br>
Android<br>
Firebase<br>
Flutter

</td>

<td valign="top" width="25%">

### 💻 Lenguajes

<p align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40"/>
<img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matlab/matlab-original.svg" width="40"/>

</p>

Python<br>
C++<br>
C<br>
Java<br>
Kotlin<br>
MATLAB

</td>

<td valign="top" width="25%">

### 🔧 Herramientas y Otros

<p align="center">

<img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" width="40"/>
<img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" width="40"/>
<img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" width="40"/>
</p>

Arduino<br>
Selenium<br>
Figma

</td>

</tr>
</table>

<br>

## 📊 Estadísticas de GitHub

<div align="center">

<a href="https://github.com/nodexs0">
  <img height=165 align="center" src="https://github-stats-extended.vercel.app/api?username=nodexs0&rank_icon=github&show_icons=true&hide_border=true&include_all_commits=true&theme=dark&title_color=4A6FA5&icon_color=6F1C38" />
</a>

  <img height=165 align="center" src="https://github-stats-extended.vercel.app/api/top-langs/?username=nodexs0&layout=compact&hide_border=true&langs_count=6&card_width=320&theme=dark&title_color=4A6FA5" />
</a>

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=nodexs0&hide_border=true&theme=dark&ring=4A6FA5&fire=6F1C38" height="165"/>

</div>

<br>

## 📫 Contacto


<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://mx.linkedin.com/in/mariano-ugalde-diaz-64b3872b8)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mudugalde@gmail.com)

</div>
<a href="https://github.com/noders0">
<img src="https://www.gitskins.com/api/section/heatmap?username=noders0&theme=github-dark&avatar=https%3A%2F%2Favatars.githubusercontent.com%2Fu%2F138817295%3Fu%3Dfee18997ede0c278ea51a77b66370aa5233b417c%26v%3D4&variant=space-shooter&v=space-jet-original-2&mode=dark" width="100%" alt="nodexs0 animated contribution jet" />
</a>
<br>

<div align="center">
<samp>Gracias por visitar mi perfil ✨</samp>
</div>
