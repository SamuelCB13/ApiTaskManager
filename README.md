# 🛠️ Task Manager – Backend

Backend del **Mini Gestor de Tareas**, desarrollado con **Laravel** y **MySQL**.
Expone una API REST con autenticación y manejo de tareas por usuario.

---

## 🚀 Tecnologías utilizadas

- **PHP 8+**
- **Laravel**
- **MySQL**
- **JWT / Token-based Auth**
- **Laravel Vite**

---

## 🔐 Autenticación

- Registro e inicio de sesión de usuarios
- Contraseñas hasheadas
- Autenticación por token

---

## 📡 Endpoints disponibles

### Auth
| Método | Endpoint        | Descripción |
|------|-----------------|-------------|
| POST | /api/register   | Registrar usuario |
| POST | /api/login      | Login y retorno de token |

### Tasks
| Método | Endpoint            | Descripción |
|------|---------------------|-------------|
| GET  | /api/tasks          | Listar tareas del usuario |
| POST | /api/tasks          | Crear nueva tarea |
| PUT  | /api/tasks/{id}     | Actualizar tarea |
| DELETE | /api/tasks/{id}   | Eliminar tarea |

---

## 🐈‍⬛ Clonar repositorio

```
git clone https://github.com/SamuelCB13/ApiTaskManager.git
```

---

## ▶️ Instalación y ejecución

### Instalar dependencias
```
composer install
```

## ▶️ Variables de entorno

```
cp .env.example .env
php artisan key:generate
```

## ⚙️ Configurar variables de entorno

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=api_task_manager
DB_USERNAME=root
DB_PASSWORD=
```

## 📚 Migraciones
#### Las migraciones están a la mano en /database/migrations

```
php artisan migrate
```

## ▶️ Ejecutar servidor
```
php artisan serve
```

## 🚀 El servidor estará disponible en:
👉 http://localhost:8000

