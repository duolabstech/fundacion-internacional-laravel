# Fundación Internacional - Sistema de Gestión Laravel

Sistema de gestión integral para Fundación Internacional desarrollado en Laravel con integración completa a Moodle.

## Características Principales

- 🎓 Gestión de Cursos, Estudiantes e Instructores
- 🔄 Sincronización Bidireccional con Moodle
- 📊 Panel de Administración Completo
- 🛡️ Sistema de Autenticación Seguro

## Tecnologías

- Laravel 12.x
- MySQL
- TailwindCSS
- Moodle Web Services API

## Instalación

```bash
git clone https://github.com/duolabstech/fundacion-internacional-laravel.git
cd fundacion-internacional-laravel
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm run build
php artisan serve
```

## Configuración de Moodle

Actualizar las variables de entorno en `.env`:

```env
MOODLE_URL=https://tu-moodle.com
MOODLE_TOKEN=tu-token-de-servicio-web
```

---

**Desarrollado para Fundación Internacional**