# Documentación Técnica - CRUD de Productos

## 📋 Descripción General

Sistema de gestión de productos desarrollado como una aplicación web Single Page Application (SPA) que permite realizar operaciones CRUD (Create, Read, Update, Delete) sobre un catálogo de productos. La aplicación utiliza localStorage del navegador como mecanismo de persistencia y ofrece funcionalidades de búsqueda en tiempo real y exportación a PDF.

## 🛠️ Tecnologías Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Framework CSS**: Bootstrap 5.3.0
- **Persistencia**: localStorage (Web Storage API)
- **Generación PDF**: jsPDF 2.5.1
- **Identificadores únicos**: Crypto.randomUUID() API

## 📁 Estructura del Proyecto

```
crud-productos/
├── index.html          # Estructura principal de la aplicación
└── localStorage.js     # Lógica de negocio y manipulación de datos
```

## ⚡ Funcionalidades Principales

### 1. Gestión de Productos
- **Crear**: Agregar nuevos productos con validación de campos
- **Leer**: Visualización de productos en tabla responsiva
- **Actualizar**: Edición de productos existentes
- **Eliminar**: Eliminación de productos con confirmación

### 2. Características Adicionales
- **Búsqueda en tiempo real**: Filtrado instantáneo por nombre de producto
- **Exportación PDF**: Generación de reportes en formato PDF
- **Interfaz responsiva**: Adaptable a diferentes tamaños de pantalla
- **Validación de formularios**: Campos obligatorios y tipos de datos

## 📖 Guía de Uso

### Agregar Producto
1. Completar todos los campos del formulario:
   - **Producto**: Nombre del producto
   - **Precio**: Valor numérico
   - **Descripción**: Descripción detallada
   - **URL Imagen**: Enlace válido a imagen
2. Hacer clic en "Guardar"

### Editar Producto
1. Hacer clic en el botón "Editar" de la fila correspondiente
2. Modificar los campos necesarios
3. Hacer clic en "Guardar"

### Eliminar Producto
1. Hacer clic en el botón "Eliminar" de la fila correspondiente
2. El producto se elimina inmediatamente

### Buscar Productos
1. Escribir en el campo de búsqueda
2. Los resultados se filtran automáticamente

### Exportar PDF
1. Hacer clic en el botón "Exportar PDF"
2. El archivo se descarga automáticamente

## 🔧 Documentación Técnica

### Arquitectura

La aplicación sigue un patrón de arquitectura simple basado en:
- **Presentación**: HTML con Bootstrap para la interfaz
- **Lógica de Negocio**: JavaScript vanilla para manipulación de datos
- **Persistencia**: localStorage para almacenamiento local

Desarrollado por: J.JDev

Con mucho ❤️🎯🚀
