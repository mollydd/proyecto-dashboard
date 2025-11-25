# **Dashboard de Gestión Académica — Proyecto Unidad 3**

Este proyecto corresponde a la **Unidad 3: Cloud Computing y buenas prácticas de desarrollo de software**, donde se implementa la interfaz gráfica (frontend) de un dashboard académico utilizando **HTML + TailwindCSS**.
Toda la información mostrada es **estática**, de acuerdo a los lineamientos del taller práctico.

---

## 🧩 **Objetivo del proyecto**

Desarrollar la vista principal del Dashboard (“Inicio”), aplicando:

- Buenas prácticas de HTML5 semántico
- Diseño responsivo
- Estilos con TailwindCSS
- Organización limpia del código
- Estructura recomendada del proyecto
- Preparación para despliegue en un servidor web (Apache en EC2)

---

## 📂 **Estructura del proyecto**

```
/proyecto-dashboard
│
├── index.html
├── style.css
├── readme.md
│
└── assets/img/
    └─ logo.png

```

---

## 🎨 **Tecnologías utilizadas**

- **HTML5 semántico**
- **TailwindCSS v4 (via CDN)**
- JavaScript básico para el menú móvil
- Buenas prácticas de maquetación recomendadas en la Unidad 3

---

## 📱 **Características del dashboard**

- Sidebar responsiva con menú deslizable en mobile
- Header fijo con avatar del usuario
- Tarjetas (cards) informativas limpias y minimalistas
- Diseño responsivo para pantallas pequeñas y grandes
- Interactividad básica con JavaScript nativo
- Layout inspirado en dashboards académicos profesionales

---

## ☁️ **Despliegue en AWS EC2**

### Pasos a realizar:

1. Crear instancia **t3.micro** en Linux Ubuntu
2. Instalar **Apache**
3. Acceder a `/var/www/html/` por SSH
4. Copiar los archivos del proyecto
5. Asignar permisos a la carpeta
6. Acceder con la URL pública en el navegador

---

## 📘 **Bitácora de tareas**

La bitácora debe registrar: fecha, desarrollador, actividad, archivos modificados, tiempo, dificultad y solución.

---

## 👥 **Autores**

- Isaac Mendoza
- Gabriel Navarro
- Aixa Martinez
- Paula Machacon
