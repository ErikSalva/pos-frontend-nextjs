# 🛍️ POS Frontend

<img width="1869" height="903" alt="image" src="https://github.com/user-attachments/assets/9fc7ac0e-1738-4a3b-bebc-2ccc405bcbe0" />

Frontend de un sistema **POS (Point of Sale / Punto de Venta)** desarrollado con **Next.js 15 + TypeScript** y **Tailwind CSS**.  
Permite a los usuarios **navegar por productos, añadirlos al carrito, aplicar cupones de descuento y realizar compras**.  
Además, cuenta con un **panel de administración** donde se pueden **gestionar productos y revisar ventas**.

---

## 🌐 Sitio en línea

🔗 [https://pos-frontend-next-w9mv.vercel.app/](https://pos-frontend-next-w9mv.vercel.app)

---
## ✨ Funcionalidades principales

- 🛒 Vista de tienda para explorar y pedir productos  
- 🎟️ Aplicación de cupones de descuento en las compras  
- 👨‍💻 Panel de administración:
  - CRUD completo de productos (crear, editar, eliminar)  
  - Visualización de ventas del día o por fecha seleccionada en el calendario  
- 🔔 Notificaciones de acciones (React Toastify)  
- 📅 Selección de fechas y calendario para administración  
- 📦 Subida de imágenes de productos con soporte de drag & drop  

---

## 🛠️ Tecnologías utilizadas

- [Next.js 15](https://nextjs.org/) + [TypeScript](https://www.typescriptlang.org/)  
- [React 19](https://react.dev/) con Server Components  
- [Tailwind CSS 4](https://tailwindcss.com/) para diseño responsivo  
- [Zustand](https://zustand-demo.pmnd.rs/) para manejo de estado  
- [TanStack React Query](https://tanstack.com/query/latest) para manejo de datos asíncronos  
- [Zod](https://zod.dev/) para validación de formularios  
- [React Toastify](https://fkhadra.github.io/react-toastify/introduction) para notificaciones  
- [React Dropzone](https://react-dropzone.js.org/) para subida de imágenes  
- [React Calendar](https://github.com/wojtekmaj/react-calendar) para administración de fechas  

---

## ⚙️ Instalación y uso

```bash
# Clonar repositorio
git clone https://github.com/ErikSalva/pos-frontend-nextjs.git

# Instalar dependencias
npm install

# Configurar variables de entorno en .env.local
# API_URL: URL del backend (no accesible desde el cliente)
# NEXT_PUBLIC_API_URL: URL del backend accesible desde el cliente
# NEXT_PUBLIC_DOMAIN: Dominio del frontend (por ejemplo http://localhost:3000)
API_URL=
NEXT_PUBLIC_API_URL=
NEXT_PUBLIC_DOMAIN=

# Ejecutar en desarrollo
npm run dev
