<div align="center">
  <h1>🎨 Figma Clone - Editor Colaborativo en Tiempo Real</h1>
  
  <p>
    <strong>Un clon básico de Figma desarrollado por SnakeDev</strong>
  </p>

  <div>
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Next.js-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextjs" />
    <img src="https://img.shields.io/badge/-React-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-JavaScript-black?style=for-the-badge&logoColor=white&logo=javascript&color=F7DF1E" alt="javascript" />
  </div>

  <br />

  <p>
    <em>Proyecto de aprendizaje para principiantes que demuestra funcionalidades de colaboración en tiempo real</em>
  </p>
</div>

---

## 📋 Tabla de Contenidos

1. [🚀 Introducción](#-introducción)
2. [⚡ Tecnologías](#-tecnologías)
3. [✨ Características](#-características)
4. [🛠️ Instalación](#️-instalación)
5. [📦 Variables de Entorno](#-variables-de-entorno)
6. [🎯 Uso](#-uso)
7. [👨‍💻 Desarrollador](#-desarrollador)

---

## 🚀 Introducción

Este es un **clon básico de Figma** diseñado como proyecto de aprendizaje para principiantes. Implementa funcionalidades clave de colaboración en tiempo real como cursores múltiples, chat en vivo, comentarios y herramientas básicas de diseño.

### 🎯 Propósito del Proyecto

- Aprender conceptos de **colaboración en tiempo real**
- Practicar **TypeScript** y **Next.js**
- Implementar **WebSockets** y sincronización de estado
- Trabajar con **canvas HTML** y manipulación de elementos

---

## ⚡ Tecnologías

Este proyecto fue construido con las siguientes tecnologías:

| Tecnología       | Uso                                               |
| ---------------- | ------------------------------------------------- |
| **Next.js**      | Framework de React para producción                |
| **TypeScript**   | Tipado estático y mejor experiencia de desarrollo |
| **React**        | Librería para construir interfaces de usuario     |
| **Tailwind CSS** | Framework de CSS para estilos rápidos             |
| **JavaScript**   | Lógica del lado del cliente                       |
| **Liveblocks**   | Colaboración en tiempo real                       |
| **Fabric.js**    | Manipulación de canvas HTML5                      |

---

## ✨ Características

### 🎨 Herramientas de Diseño

- ✏️ **Dibujo libre** - Dibuja libremente sobre el canvas
- 🔷 **Formas geométricas** - Crea rectángulos, círculos, triángulos, etc.
- 🖼️ **Carga de imágenes** - Importa y manipula imágenes
- 🎨 **Personalización** - Ajusta colores, tamaños y propiedades

### 👥 Colaboración en Tiempo Real

- 🖱️ **Cursores múltiples** - Ve el cursor de cada usuario en tiempo real
- 💬 **Chat de cursor** - Chatea directamente desde tu cursor
- 😊 **Reacciones** - Expresa emociones con reacciones rápidas
- 👤 **Usuarios activos** - Lista de usuarios conectados en tiempo real

### 💭 Sistema de Comentarios

- 📌 **Comentarios anclados** - Agrega comentarios a elementos específicos
- 🔔 **Notificaciones** - Recibe alertas de nuevos comentarios
- ✅ **Resolver comentarios** - Marca comentarios como resueltos

### 🔧 Funcionalidades Adicionales

- ↩️ **Deshacer/Rehacer** - Revierte o restaura acciones
- ⌨️ **Atajos de teclado** - Mejora tu productividad
- 📜 **Historial** - Revisa cambios anteriores
- 🗑️ **Gestión de elementos** - Elimina, escala, mueve elementos
- 💾 **Exportar canvas** - Descarga tu diseño final

---

## 🛠️ Instalación

### Prerrequisitos

Asegúrate de tener instalado:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (v16 o superior)
- [npm](https://www.npmjs.com/) o [yarn](https://yarnpkg.com/)

### Pasos de Instalación

1. **Clona el repositorio**

```bash
git clone https://github.com/tu-usuario/figma-clone.git
cd figma-clone
```

2. **Instala las dependencias**

```bash
npm install
# o
yarn install
```

3. **Configura las variables de entorno** (ver sección siguiente)

4. **Inicia el servidor de desarrollo**

```bash
npm run dev
# o
yarn dev
```

5. **Abre tu navegador**

Visita [http://localhost:3000](http://localhost:3000)

---

## 📦 Variables de Entorno

Crea un archivo `.env.local` en la raíz del proyecto:

```env
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=pk_tu_clave_aqui
```

### 🔑 Cómo obtener la clave de Liveblocks

1. Ve a [liveblocks.io](https://liveblocks.io)
2. Crea una cuenta o inicia sesión
3. Crea un nuevo proyecto
4. Copia tu **Public Key** (comienza con `pk_`)
5. Pégala en el archivo `.env.local`

---

## 🎯 Uso

### Controles Básicos

- **Click** - Seleccionar elementos
- **Arrastrar** - Mover elementos
- **Ctrl/Cmd + C** - Copiar
- **Ctrl/Cmd + V** - Pegar
- **Ctrl/Cmd + Z** - Deshacer
- **Delete** - Eliminar elemento seleccionado

### Herramientas

1. **Selección** - Haz click en elementos para seleccionarlos
2. **Formas** - Usa la barra lateral para crear formas
3. **Dibujo** - Activa el modo de dibujo libre
4. **Comentarios** - Click en el botón de comentarios para añadir uno

---

## 👨‍💻 Desarrollador

<div align="center">
  <h3>🐍 SnakeDev</h3>
  <p>Desarrollador Full Stack en formación</p>
  
  <p>
    <em>Este proyecto fue creado como parte de mi aprendizaje en desarrollo web y colaboración en tiempo real.</em>
  </p>
</div>

---

## 📝 Notas del Desarrollador

Este es un proyecto de **nivel principiante** creado con fines educativos. El objetivo principal es:

- ✅ Entender cómo funcionan las aplicaciones colaborativas
- ✅ Practicar TypeScript y Next.js
- ✅ Implementar características en tiempo real
- ✅ Trabajar con canvas y manipulación de DOM

**No es un clon completo de Figma**, sino una versión simplificada que cubre las funcionalidades básicas.

---

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

---

<div align="center">
  <p>Hecho con ❤️ por <strong>SnakeDev</strong></p>
  <p>⭐ Si te gustó este proyecto, no olvides darle una estrella</p>
</div>
