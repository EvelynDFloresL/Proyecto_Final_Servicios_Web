# 📚 Proyecto Final - Servicios Web

## 🚀 Descripción General

Este proyecto está compuesto por dos aplicaciones que interactúan entre sí:

- **Un administrador web desarrollado en Flask**, encargado del manejo de contenido mediante operaciones CRUD.
- **Una interfaz de usuario** donde los consumidores pueden visualizar productos, realizar búsquedas y suscribirse para acceder a contenido completo.

Este servicio permite a los usuarios consultar un catálogo de títulos, acceder a su contenido y suscribirse para desbloquear funcionalidades adicionales.

---

## 🖥️ Interfaces del Administrador (Flask)

Administrador que permite gestionar el contenido mostrado a los usuarios.

### 🔐 Inicio de Sesión del Administrador
![Inicio de Sesión Admin](https://github.com/user-attachments/assets/e8de5e4c-d8b1-4f02-abae-652d11707b4a)

### 📝 Registro de Administradores
![Registro](https://github.com/user-attachments/assets/2a0660ec-60e4-41d5-9a69-dcda589d2052)

### 🛠️ Panel CRUD del Administrador
![CRUD del Admin](https://github.com/user-attachments/assets/1328d44a-e0c8-4679-a8d4-84644b89091e)

---

## 📱 Interfaces del Usuario Final

Interfaz web para que los usuarios puedan explorar el catálogo, suscribirse y buscar productos.

### 🏠 Página de Inicio
![Inicio](https://github.com/user-attachments/assets/0e0ed2f7-5586-4784-bae4-9ea1b774ea1f)

### 📩 Suscripción
![Suscripcion](https://github.com/user-attachments/assets/aa264e60-96bd-4565-8f71-bb86d16d65e5)

### 📦 Productos desde Firebase
![Productos que se obtienen de firebase](https://github.com/user-attachments/assets/d1db721c-0da2-4814-be30-373c770dbfc9)

### 🔍 Buscador de Productos
![Buscador de Productos](https://github.com/user-attachments/assets/beef7d02-d87d-452e-b754-903d15a16029)

---

## 🧩 Arquitectura General

![Vista general del sistema](https://github.com/user-attachments/assets/9c744fe2-548a-45bf-ac4f-5c56289467c1)
![Diagrama de flujo del servicio](https://github.com/user-attachments/assets/a47c0888-b8f7-485e-a68c-86fd3db83056)

---

## 🔧 Servicios Implementados

### 🛒 Servicio 1: CRUD de Inventario (Administrador)

#### 🛠️ Tecnologías Utilizadas
- **Lenguaje:** Python
- **Framework:** Flask
- **Funcionalidad Principal:** Gestión CRUD de productos (crear, leer, actualizar, eliminar).

---

### 📺 Servicio 2: Suscripciones y Visualización de Contenido (Usuario)

#### 🛠️ Tecnologías Utilizadas
- **Lenguaje:** HTLML, CSS, PHP y Python
- **Frameworks:** Slim (PHP) y Flask (Python)
- **Funcionalidad Principal:** 
  - Gestión de suscripciones.
  - Visualización de contenido limitado sin suscripción.
  - Acceso completo al catálogo solo para usuarios suscritos.

---

## 🧪 Funcionalidades Clave

1. 📖 **Visualización de Libros:**
   - Catálogo de títulos accesible al público.
2. ✍️ **Suscripción de Usuarios:**
   - Desbloqueo de contenido completo al suscribirse.
3. 🧑‍💼 **Administrador del Sistema:**
   - Control total del contenido a través de un panel CRUD.
4. 🔍 **Buscador de Productos:**
   - Búsqueda del producto.
---





