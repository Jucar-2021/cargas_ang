# Proyecto Grúas ANG

## 🚀 Configuración del Logo

Para que la aplicación muestre el logo de la empresa:

1. Agrega tu logo en la carpeta `assets/images/` con el nombre `logo_gruas_ang.png`
2. Dimensiones recomendadas: 512x512 px o similar
3. Formato: PNG con fondo transparente (preferiblemente)

**Nota:** Si no aggregates el logo, la aplicación mostrará un placeholder con un ícono de camión y el texto "GRÚAS ANG".

## 📱 Características Implementadas

### Página de Login
- Logo de la empresa
- Campo de correo electrónico con validación
- Campo de contraseña con opción de mostrar/ocultar
- Botón de "¿Olvidaste tu contraseña?"
- Opción de registro
- Diseño moderno con Material 3

### Página Principal (Home)
- AppBar con título y acciones
- Menú lateral (Drawer) con opciones:
  - Dashboard
  - Cargas
  - Rutas
  - Historial
  - Configuración
  - Cerrar Sesión
- Tarjetas de estadísticas:
  - Cargas Activas
  - En Tránsito
  - Completadas
  - Pendientes
- Botón flotante para agregar nueva carga

## 🎨 Colores del Tema
- Color principal: Deep Purple
- Fondo: Blanco
- Acentos según tipo de información

## ▶️ Cómo ejecutar

```bash
flutter pub get
flutter run
```

## 📝 Próximos pasos sugeridos

1. Agregar el logo real de la empresa
2. Implementar lógica de autenticación
3. Conectar con backend/base de datos
4. Desarrollar las funcionalidades de cada sección del menú
5. Agregar manejo de estados (Provider, Bloc, Riverpod, etc.)

