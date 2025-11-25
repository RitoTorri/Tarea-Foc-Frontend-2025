
# 🚀 Tarea FOC - Frontend 2025

¡Bienvenido al proyecto frontend desarrollado para la asignatura de Fundamentos de Computación!

## 👥 **Equipo de Desarrollo**

| Nombre |
|---------|
| Jesús Cortez |
| Jesús Camacho |
| Santiago Rodriguez |
| Erika |

---

## 📋 **Requisitos del Sistema**

- **Node.js** (versión 16 o superior)
- **NPM** (viene incluido con Node.js)
- **Conexión a internet** (para instalar dependencias)

---

## 🔗 **Dependencias Principales**

| Paquete | Versión | Propósito |
|---------|---------|-----------|
| `vue` | ^3.3.0 | Framework principal |
| `axios` | ^1.6.0 | Cliente HTTP para API |
| `vue-router` | ^4.2.0 | Enrutamiento de la aplicación |

---

## ⚡ **Instalación Rápida**

### 1. **Clonar el Repositorio**
```bash
git clone https://github.com/RitoTorri/Tarea-Foc-Frontend-2025
cd Tarea-Foc-Frontend-2025
```

### 2. **Instalar Dependencias**
```bash
npm install
```

### 3. **Configurar Variables de Entorno**

Crea un archivo `.env` en la raíz del proyecto con:

```env
VITE_API_URL=http://localhost:3785/api/v1
```

> **⚠️ IMPORTANTE:** Necesitas el [Backend de la API](https://github.com/RitoTorri/Tarea-Foc-Backend-2025) ejecutándose localmente.

### 4. **Ejecutar la Aplicación**
```bash
npm run dev
```

### 5. **Acceder a la Aplicación**
```
🌐 Local:    http://localhost:5173/
```

Presiona `Ctrl + Click` en la URL o ábrela manualmente en tu navegador.


## 🚀 **Funcionamiento del Sistema**

### 🎯 **Propósito Principal**
Este proyecto funciona como un cliente frontend especializado que consume una API REST para visualizar y consultar información almacenada en una base de datos. Su enfoque está exclusivamente en la presentación de datos mediante operaciones de lectura.

### 📊 **Características de Operación**

#### 🔍 **Solo Consultas (Operaciones GET)**
- Visualización de datos en tiempo real desde la base de datos
- Múltiples módulos disponibles para consulta
- Interfaz de solo lectura - diseñada específicamente para mostrar información

#### 🧭 **Sistema de Navegación**
- Barra de navegación intuitiva que organiza los diferentes módulos
- Acceso rápido entre secciones sin recargar la página
- Experiencia de usuario fluida con transiciones entre vistas

#### 📋 **Presentación de Datos**
- Tablas dinámicas que muestran la información de forma estructurada
- Formato consistente across todos los módulos
- Datos organizados con columnas claras y legibles
