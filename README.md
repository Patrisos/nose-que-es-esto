# Mi Página Web - Firebase Hosting

Una página web simple y moderna desplegada en Firebase Hosting.

## 🚀 Estructura del Proyecto

```
├── public/
│   ├── index.html    # Página principal
│   └── styles.css    # Estilos CSS
├── firebase.json     # Configuración de Firebase
├── .firebaserc       # Configuración del proyecto Firebase
└── README.md
```

## 📋 Requisitos Previos

1. Tener Node.js instalado
2. Tener una cuenta de Firebase
3. Instalar Firebase CLI

## 🔧 Instalación

### 1. Instalar Firebase CLI

```powershell
npm install -g firebase-tools
```

### 2. Iniciar sesión en Firebase

```powershell
firebase login
```

### 3. Configurar el proyecto

Edita el archivo `.firebaserc` y reemplaza `"tu-proyecto-firebase"` con el ID de tu proyecto de Firebase:

```json
{
  "projects": {
    "default": "tu-proyecto-firebase"
  }
}
```

> **Nota:** Puedes encontrar el ID de tu proyecto en la [consola de Firebase](https://console.firebase.google.com/).

## 🚀 Despliegue

### Desplegar a Firebase Hosting

```powershell
firebase deploy
```

### Ver la página localmente (opcional)

```powershell
firebase serve
```

La página estará disponible en `http://localhost:5000`

## 🌐 URL del Sitio

Una vez desplegado, tu sitio estará disponible en:
- `https://tu-proyecto-firebase.web.app`
- `https://tu-proyecto-firebase.firebaseapp.com`

## 📝 Comandos Útiles

| Comando | Descripción |
|---------|-------------|
| `firebase login` | Iniciar sesión en Firebase |
| `firebase logout` | Cerrar sesión |
| `firebase serve` | Servidor local de desarrollo |
| `firebase deploy` | Desplegar a producción |
| `firebase deploy --only hosting` | Desplegar solo hosting |

## 🎨 Personalización

- Edita `public/index.html` para cambiar el contenido
- Edita `public/styles.css` para modificar los estilos