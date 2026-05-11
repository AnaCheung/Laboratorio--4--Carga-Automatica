# 🧪 Laboratorio - Implementación de Autocarga PSR-4 con Composer

## 📖 Introducción

Este laboratorio implementa la carga automática de clases utilizando el estándar PSR-4 junto con Composer en PHP.

El objetivo es eliminar el uso manual de include y require mediante Namespaces y autoload.

---

# ⚙️ Requisitos

- PHP 8 o superior
- Composer instalado
- Visual Studio Code

---

# 🚀 Instalación

## 1. Clonar el repositorio

```bash
git clone URL_DEL_REPOSITORIO
```

## 2. Entrar al proyecto

```bash
cd AUTOCARGAAUTOMATICA
```

## 3. Generar autoload

```bash
composer dump-autoload
```

---

# 📂 Estructura del Proyecto

```txt
AUTOCARGAAUTOMATICA/
│
├── App/
│   └── User.php
│
├── Database/Model/
│   └── ProductModel.php
│
├── composer.json
├── prueba.php
└── vendor/
```

---

# 🧠 Funcionamiento

Composer utiliza PSR-4 para cargar automáticamente las clases usando namespaces.

Ejemplo:

```php
use App\User;
```

Sin necesidad de usar include o require manualmente.

---

# 🖥️ Ejemplo de Ejecución

```php
require 'vendor/autoload.php';

use App\User;

$user = new User();
```

---
---

# 📸 Evidencias

## ✔ Generación correcta del Autoload con Composer

En la siguiente evidencia se observa la ejecución exitosa del comando:

```bash
composer dump-autoload
```

<p align="center">
  <img width="585" height="67" alt="Captura de pantalla 2026-05-11 144856" src="https://github.com/user-attachments/assets/7206dcee-f1e9-4f0b-bd06-f9ac4882d8f4" />
</p>

---

## ✔ Ejecución correcta del programa

<p align="center">
  <img width="524" height="67" alt="Captura de pantalla 2026-05-11 144500" src="https://github.com/user-attachments/assets/e9b8327b-b4d0-4b12-98fb-f4c8acb63f77" />
</p>

---

# 📚 Conclusiones Técnicas

## 1. Mantenibilidad

Permite agregar nuevas clases fácilmente.

## 2. Eficiencia

Las clases se cargan únicamente cuando se necesitan.

## 3. Organización

PSR-4 mantiene una estructura limpia y profesional.

---
