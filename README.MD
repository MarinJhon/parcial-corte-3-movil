# Parcial Corte 3 - Desarrollo Móvil

## 📋 Descripción del Proyecto

Este repositorio contiene la estructura y archivos necesarios para implementar una nueva pantalla de **Registro de Puntos** en una aplicación móvil. La pantalla gestiona puntos con los siguientes campos:

- **id**: Identificador único
- **title**: Título del punto
- **description**: Descripción detallada
- **date**: Fecha de registro
- **status**: Estado del punto (activo/inactivo)

## 🎯 Objetivo de la Prueba

Crear una pantalla funcional de Registro de Puntos que:
- Muestre una lista de puntos registrados
- Permita visualizar los detalles de cada punto
- Incluya estilos y consumo de API
- Sea compatible con la arquitectura del proyecto principal

**Tiempo de desarrollo**: 30 minutos

## 📁 Estructura del Proyecto * de acuerdo a su proyecto (vue / angular / react)

```
src/
├── components/
│   ├── PointCard.tsx          # Componente de tarjeta para mostrar cada punto
│   └── PointForm.tsx           # Componente de formulario para crear/editar puntos
├── views/
│   ├── PointsListView.tsx      # Vista principal con la lista de puntos
│   └── PointDetailView.tsx     # Vista de detalle de un punto específico
├── router/
│   └── pointsRoutes.tsx        # Configuración de rutas para las vistas de puntos
├── services/
│   └── pointsService.ts        # Servicio para consumir la API de puntos
└── styles/
    └── pointsStyles.css        # Estilos específicos para las vistas de puntos
```

## 🚀 Instalación y Uso

### 1. Clonar el Repositorio

```bash
git clone https://github.com/code-corhuila/parcial-corte-3-movil.git
cd parcial-corte-3-movil
```

### 2. Integrar en tu Proyecto

Copia la carpeta `src` completa a tu proyecto principal (solo lo necesario): 



## 🎨 Características Implementadas - esperadas - las que hizo su proyecto

### Componentes

- ✅ **PointCard**: Tarjeta reutilizable para mostrar información resumida de un punto
- ✅ **PointForm**: Formulario completo con validación para crear/editar puntos

### Vistas

- ✅ **PointsListView**: Lista scrolleable con todos los puntos
- ✅ **PointDetailView**: Vista detallada con toda la información del punto

### Servicios

- ✅ **pointsService**: CRUD completo (Create, Read, Update, Delete)
- ✅ Manejo de errores
- ✅ Tipado con TypeScript

### Estilos

- ✅ Diseño responsivo
- ✅ Tema consistente con colores y tipografía
- ✅ Animaciones y transiciones suaves

- Universidad: Corporación Universitaria del Huila - CORHUILA