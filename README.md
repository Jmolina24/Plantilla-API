# 🚀 Plantilla Base para Proyectos Node.js + TypeScript 🚀

Esta plantilla proporciona una estructura inicial para proyectos en Node.js con TypeScript, facilitando un desarrollo modular y escalable.  

## 📂 Estructura del Proyecto  

```
mi-proyecto/
├── src/
│   ├── config/          # Configuraciones y variables de entorno
│   │   ├── envs.ts      # Variables de entorno
│   │   └── index.ts     # Configuración inicial
│   ├── presentation/    # Capa de presentación (Rutas y controladores)
│   │   ├── api/
│   │   │   ├── api.controller.ts  # Controladores de la API
│   │   │   ├── api.routes.ts      # Rutas específicas de la API
│   │   ├── routes.ts   # Rutas generales
│   │   ├── server.ts   # Servidor principal
│   │   └── app.ts      # Configuración de la aplicación
├── .env                # Variables de entorno
├── .env.example        # Archivo de ejemplo para variables de entorno
├── .gitignore          # Archivos y carpetas ignoradas por Git
├── nodemon.json        # Configuración de Nodemon para recarga automática
├── package.json        # Dependencias y configuración del proyecto
├── package-lock.json   # Registro de dependencias
├── tsconfig.json       # Configuración de TypeScript
└── README.md           # Documentación del proyecto
```

## 🚀 Instalación  

### 1️⃣ Clonar el repositorio  
```sh
git clone https://github.com/usuario/mi-plantilla.git
cd mi-plantilla
```

### 2️⃣ Instalar dependencias  
```sh
npm install
```

### 3️⃣ Configurar variables de entorno  
Renombrar `.env.example` a `.env` y ajustar las variables necesarias.  

### 4️⃣ Iniciar el servidor en desarrollo  
```sh
npm run dev
```

## 🛠️ Tecnologías Utilizadas  

- **Node.js** + **Express** 🟢  
- **TypeScript** ⚡  
- **Dotenv** para manejo de variables de entorno ⚙️  
- **Env-var** para validación de variables de entorno 🔍  
- **Nodemon** para recarga automática 🔄  
- **Rimraf** para limpieza de archivos temporales 🗑️  
- **TS-Node** para ejecutar TypeScript sin compilación previa 🚀  
- **JWT (JSON Web Tokens)** para autenticación 🔐 *(Pendiente de agregar en dependencias)*  
- **Swagger** para documentación 📄 *(Pendiente de agregar en dependencias)*  
- **MongoDB / SQL Server / PostgreSQL / MySQL** 🗄️ *(Pendiente de agregar en dependencias si aplica)*  
 

## 📜 Licencia  

Este proyecto está bajo la licencia MIT, disponible para cualquier uso.  

## 👤 Autor  

📌 **GitHub:** [Jmolina24](https://github.com/Jmolina24)  
