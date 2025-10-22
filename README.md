# biblioteca

# 📚 Proyecto Web Django: Biblioteca Digital

## 🚀 Funcionalidades

1. Herencia de HTML (`base.html`).
2. Tres modelos (`Libro`, `Autor`, `Editorial`).
3. Formularios para agregar libros.
4. Búsqueda de libros.
5. Registro, login, logout de usuarios.
6. Edición de perfil de usuario.
7. Control de sesiones (solo usuarios logueados pueden agregar libros).
8. Página 404 personalizada.

## 🧭 Orden para probar

1. Ir a `/registro/` → crear usuario.
2. Ir a `/login/` → iniciar sesión.
3. Ir a `/agregar/` → agregar libros.
4. Ir a `/buscar/?q=algo` → buscar libros.
5. Ir a `/perfil/` → editar datos del usuario.
6. Probar una URL inexistente → ver página 404.
7. `/logout/` → cerrar sesión.

## 👤 Superusuario (para admin)
- Usuario: `admin`
- Contraseña: la que creaste en el Colab.

## 🧱 Estructura principal
- App principal: `libros`
- Base de datos: SQLite3
- Framework: Django
- Entorno: Google Colab + ngrok
MD
