# Portafolio Profesional – José Alejandro Fiengo

Este repositorio contiene mi portafolio profesional, desarrollado con [Hugo](https://gohugo.io/) y desplegado automáticamente en [GitHub Pages](https://pages.github.com/) utilizando el tema [PaperMod](https://github.com/adityatelange/hugo-PaperMod).

📍 **Sitio en vivo:**
👉 [https://alefiengo.github.io/portafolio/](https://alefiengo.github.io/portafolio/)

---

## 🌟 Objetivo

Este sitio web funciona como mi espacio profesional público, donde presento:

* Una descripción de mi perfil técnico
* Proyectos destacados en los que he participado
* Artículos y contenidos sobre desarrollo, arquitectura y DevOps
* Canales de contacto profesional

---

## 🛠 Tecnologías utilizadas

| Herramienta                                                | Descripción                                     |
| ---------------------------------------------------------- | ----------------------------------------------- |
| [Hugo](https://gohugo.io/)                                 | Generador de sitios estáticos rápido y flexible |
| [PaperMod](https://github.com/adityatelange/hugo-PaperMod) | Tema minimalista, profesional y extensible      |
| [GitHub Actions](https://github.com/features/actions)      | CI/CD para automatizar builds y despliegue      |
| [GitHub Pages](https://pages.github.com/)                  | Hosting estático gratuito                       |

---

## ⚙️ Estructura del proyecto

```plaintext
.
├── content/           # Secciones principales (sobre mí, proyectos, blog, contacto)
├── layouts/           # Archivos personalizados (opcional)
├── static/            # Recursos estáticos (imágenes, CSS propio, etc.)
├── themes/PaperMod/   # Tema PaperMod como submódulo o clonado directamente
├── config.toml        # Configuración principal del sitio
└── .github/workflows/ # Workflow para despliegue automático en GitHub Pages
```

---

## 🚀 Despliegue automático

Cada vez que hago push a la rama `main`, GitHub Actions construye el sitio con Hugo y lo despliega automáticamente en `gh-pages`.

Este proceso incluye:

* Clonación del repositorio con submódulos (tema incluido)
* Compilación con Hugo Extended
* Publicación en GitHub Pages (entorno `github-pages`)

---

## ✍️ Licencia

El contenido del portafolio es de mi autoría. El tema [PaperMod](https://github.com/adityatelange/hugo-PaperMod) se distribuye bajo la licencia MIT.

---

## 📬 Contacto

Puedes encontrarme en:

* GitHub: [@alefiengo](https://github.com/alefiengo)
* LinkedIn: [José Alejandro Fiengo Vega](https://www.linkedin.com/in/jos%C3%A9-alejandro-fiengo-vega-383560165)
* Email: [jose.fiengo.vega@gmail.com](mailto:jose.fiengo.vega@gmail.com)
