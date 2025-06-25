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
3. Pega la URL de este repositorio
4. Selecciona **"Docker Compose"** como Build Pack
5. Configura:
   - **Base Directory**: `/`
   - **Docker Compose Location**: `/docker-compose.yml`

### Configuración de Variables

Coolify detectará automáticamente las variables del compose. Configura:

- `POSTGRES_PASSWORD`: Contraseña para PostgreSQL
- `POSTGRES_NON_ROOT_PASSWORD`: Contraseña para usuario N8N
- `SUPABASE_DB_PASSWORD`: Contraseña para Supabase
- `SUPABASE_JWT_SECRET`: Secret JWT de 32 caracteres

## 📊 Servicios y Acceso

| Servicio | Puerto | Acceso |
|----------|--------|---------|
| N8N | 5678 | https://tu-dominio.com |
| Qdrant | 6333 | https://qdrant.tu-dominio.com |
| Supabase API | 3000 | https://supabase.tu-dominio.com |

## 🛠️ Herramientas Incluidas

### FFmpeg
Procesamiento completo de audio y video integrado

### yt-dlp
Descarga de contenido de YouTube y +1000 sitios

### Librerías de IA
- OpenAI, Anthropic
- LangChain, Transformers
- TensorFlow, PyTorch
- Qdrant para búsquedas vectoriales

### Librerías JavaScript/Python
- Manipulación de datos (pandas, lodash)
- APIs y scraping (axios, requests, beautifulsoup)
- Bases de datos (psycopg2, redis)

## 📝 Instrucciones Detalladas

Para instrucciones paso a paso completas sobre configuración y uso, consulta la documentación incluida en el repositorio.

## 📄 Licencia

MIT License - Libre para uso comercial y personal.

---

**⭐ Si este proyecto te ayuda, considera darle una estrella!**
