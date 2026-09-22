# Taller Admin

Web App + PWA administrativa conectada al backend Supabase del taller.

## Backend
Proyecto Supabase: `puxzsxhrlghbzatzsiyg`

## Módulos conectados
- Dashboard
- Órdenes de trabajo
- Clientes y vehículos
- Empleados y roles
- Cotizaciones
- Recibos
- Inventario
- Reportes
- Ajustes de marca

## Primer acceso
1. Publica el sitio con GitHub Pages.
2. Abre Taller Admin.
3. Usa **Crear primer administrador**.
4. La primera cuenta confirmada reclama el rol `admin`.
5. Desde **Empleados** crea accesos para gerente, mecánico o ayudante.

## Seguridad
- Supabase Auth por email/contraseña
- Row Level Security en las tablas
- Empleados solo ven órdenes asignadas
- Evidencias en bucket privado
- Creación de empleados protegida por Edge Function con validación de rol
