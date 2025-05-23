# Counter App

Una aplicación React simple con contador, autenticación y rutas protegidas usando Redux Toolkit.

## Características

-  **Contador**: Incrementar y decrementar valores
-  **Autenticación**: Sistema de login/logout básico
-  **Rutas Protegidas**: El contador solo es accesible después del login

## Tecnologías

- React
- Redux Toolkit
- React Router DOM
- CSS
- Bootstrap Icons

## Instalación

```bash
# clonar el repositorio
git clone https://github.com/fg-dev-e/redux-auth.git

# instalar dependencias
npm i

# ejecutar en dev mode
npm run dev
```

## Estructura del Proyecto

```
src/
├── components/
│   ├── Navbar.jsx
│   └── ProtectedRoute.jsx
├── features/
│   ├── auth/
│   │   └── authSlice.js
│   └── counter/
│       └── counterSlice.js
├── pages/
│   ├── Home.jsx
│   └── Counter.jsx
├── app/
│   └── store.js
└── App.jsx
```

## Uso

1. **Acceder a la aplicación**: La página de inicio es pública
2. **Hacer Login**: Hacer clic en "Login" en la barra de navegación
3. **Usar el Contador**: Una vez autenticado, acceder a counter para usar el contador
4. **Logout**: Hacer clic en "Logout" para cerrar sesión