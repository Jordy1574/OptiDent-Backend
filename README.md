# 🦷 OptiDent - Backend

Este es el servidor del proyecto OptiDent, desarrollado con **Node.js**, **Express** y **PostgreSQL**.

## 🚀 Requisitos previos

Antes de empezar, asegúrate de tener instalado:
* **Node.js**: Versión 22.16.0 o superior (compatible con v24).
* **npm**: Gestor de paquetes que viene con Node.
* **PostgreSQL**: Base de datos instalada localmente.

## 🛠️ Instalación y Configuración
1. **Clonar el repositorio** y entrar a la carpeta:
   ```bash
   cd OptiDent-Backend


Instalar las dependencias:

npm install

## Variables de Entorno:
Crea un archivo .env en la raíz de esta carpeta y agrega tus credenciales de PostgreSQL (no subas este archivo a GitHub):

PORT=3000
DB_USER=tu_usuario
DB_PASSWORD=tu_contraseña
DB_HOST=localhost
DB_NAME=optident_db
DB_PORT=5432


Modo Desarrollo (con reinicio automático):
npm run dev

Modo Producción:
 npm start
 
