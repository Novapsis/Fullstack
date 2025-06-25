# 🚀 N8N Automation Stack Completo

Stack completo de automatización empresarial con N8N, incluyendo todas las herramientas necesarias para proyectos de automatización avanzada.

## 📋 Componentes Incluidos

- **N8N**: Plataforma de automatización con interfaz visual
- **PostgreSQL**: Base de datos principal
- **Redis**: Cache y gestión de colas
- **Qdrant**: Base de datos vectorial para IA
- **Supabase**: Backend como servicio
- **FFmpeg**: Procesamiento de audio/video
- **yt-dlp**: Descarga de contenido multimedia
- **Librerías de Python**: IA, ML, análisis de datos
- **Librerías de JavaScript**: Manipulación de datos, APIs

## 🎯 Características Especiales

- ✅ **Listo para producción**: Configurado con health checks y restart automático
- ✅ **Optimizado para Coolify**: Variables mágicas incluidas
- ✅ **Escalable**: Redis para colas, PostgreSQL para persistencia
- ✅ **IA Ready**: Incluye Qdrant, librerías ML/AI
- ✅ **Multimedia**: FFmpeg y yt-dlp preinstalados
- ✅ **Seguro**: Configuración de usuarios y permisos

## 🚀 Despliegue en Coolify

### Opción 1: Desde la URL del Repositorio

1. En tu proyecto Coolify, haz clic en **"Create New Resource"**
2. Selecciona **"Public Repository"**
3. Pega la URL: `https://github.com/TU-USUARIO/n8n-automation-stack`
4. Selecciona **"Docker Compose"** como Build Pack
5. Configura:
   - **Base Directory**: `/`
   - **Docker Compose Location**: `/docker-compose.yml`

### Opción 2: Raw Compose Deployment

Para control total, usa el Raw Compose Deployment en Coolify y copia directamente el contenido del `docker-compose.yml`.

## ⚙️ Configuración

### Variables de Entorno Requeridas

Copia el archivo `.env.example` como base y configura:

