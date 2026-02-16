# 🚀 Proyecto Laravel

Aplicación desarrollada con Laravel utilizando un Starter Kit.

---

## 🛠️ Tecnologías Utilizadas

- PHP 8.3  
- Composer  
- MySQL  
- Node.js 20 o superior  
- NPM  

---

## 📦 Requisitos Previos

Asegúrate de tener instalado en tu sistema:

- PHP >= 8.3  
- Composer  
- MySQL  
- Node.js >= 20  
- NPM  

Puedes verificar las versiones con:

```bash
php -v
composer -V
node -v
npm -v
```

---

## ⚙️ Instalación del Proyecto

Sigue estos pasos para instalar y ejecutar el proyecto en tu entorno local:

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
cd nombre-del-proyecto
```

---

### 2️⃣ Instalar dependencias de PHP

```bash
composer install
```

---

### 3️⃣ Crear archivo de entorno

En Linux / Mac:

```bash
cp .env.example .env
```

En Windows:

```bash
copy .env.example .env
```

---

### 4️⃣ Generar clave de aplicación

```bash
php artisan key:generate
```

---

### 5️⃣ Configurar base de datos

Editar el archivo `.env` y configurar:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nombre_base_datos
DB_USERNAME=usuario
DB_PASSWORD=contraseña
```

---

### 6️⃣ Ejecutar migraciones

```bash
php artisan migrate
```

---

### 7️⃣ Instalar dependencias de Node

```bash
npm install
```

---

## ▶️ Ejecutar el Proyecto

Para correr el proyecto en entorno de desarrollo:

```bash
composer run dev
```

Esto iniciará el servidor junto con Vite para compilar los assets.

El proyecto estará disponible en:

```
http://127.0.0.1:8000
```

---

## 📁 Estructura del Proyecto

- `app/` → Lógica principal  
- `routes/` → Definición de rutas  
- `resources/` → Vistas y assets  
- `database/` → Migraciones y seeders  
- `bootstrap/` → Configuración del framework  

---

## 👨‍💻 Autor

Desarrollado por Cristian Perdomo 🚀
